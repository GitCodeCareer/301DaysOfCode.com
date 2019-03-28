# 301DaysOfCode.com

## To Do

Clean up repo & remove unneeded pages, directories & assets to make the home page display.

### [Design Document](https://medium.freecodecamp.org/how-to-write-a-good-software-design-document-66fcf019569c)

#### Overview - High Level Summary

- Note: The use of "participants" & "users" may be used interchangeably; "users" most often, for brevity.

- #301DaysOfCode empowers programmers - new and experienced - by challenging them to form a consistent programming study habit over 301 days.
- Additionally, by proxy - helps programmers with career advice through it's parent organization [CodeCareer.org](http://CodeCareer.org)
- Primarily, the website 301DaysOfCode.com serves as an informative tool about the challenge's guidelines.
  - Secondarily, acts as a service to help programers keep track of their progress in a centralized location.
  - Finally, the website highlights participants who have completed the challenge.

#### Context - Description of The Problem at Hand

- Presently users can post their progress to social media networks directly - Twitter being the primary - however, users cannot ~~~easily~~~ track and share their progress or challenge completeness as a whole.
- While the option to create a "moment" on Twitter will allow users to collect their progress in one place, do so retroactively is a large challenge.
- Our aim is to help users aggregate their challenge data in one, easy to access, cleanly presentable, public profile.

#### Goals and Non-Goals

##### Goals

- To create an aggregation tool for users.
- Enable users to post a daily challenge update on one website 301DaysOfCode.com & then distribute/share their progress on a multitude of social networks.
  - LinkedIn, Twitter, FaceBook & Dev.to being to primary focus.
- To create a cleanly presentable profile of users coding journey that can be shared with hiring managers & other interested parties.

##### Non-Goals

- To create a social network for programmers. [CodeCareer.org](http://CodeCareer.org) & existing social networks will serve this purpose.
- Manage critical user data such as emails. We will attempt to minimize user privacy or security concerns wherever possible.
  - We will differ to social authentication because the nature of this challenge is inherently social.

#### Milestones

1. User authentication system - in which users can sign up & in via existing Twitter, GitHub, LinkedIn, Facebook or Google accounts.
1. User profile layout - profile picture, description, links to Twitter, GitHub, LinkedIn, Facebook or Dev.to accounts & challenge update posts.
1. User posting feature - limited to 280 characters; so that posts are shareable on character limited networks like Twitter.
1. Historical post parsing - find instances of posts users have made in the past on the social networks mentioned above that cite "#301DaysOfCode" || "301DaysOfCode" && "Day" || "D" in any reasonable permutation.
1. Historical post importing - helps users comb through their old #301DaysOfCode posts and display the data on their profile page.