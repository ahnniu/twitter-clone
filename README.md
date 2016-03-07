# Twitter Cone

This a twitter clone to teach me Ruby on Rails.


## How to

```bash
# Install [Ruby Version Manager (RVM)](https://rvm.io/)
$ \curl -sSL https://get.rvm.io | bash -s stable
# Install Ruby
$ rvm install 2.1.5
$ bash --login
$ git clone https://github.com/ahnniu/twitter_clone.git
$ cd twitter_clone
$ gem install bundle
$ bunlde install
$ rails server
```


## Feature

- User
    + Sign up
        * Validation from email
    + Sign in
    + Forget password
    + Following and Followers
    + User Porfile / Settings
- Microblog
    + Activities with followed users microblog
    + New microblog
        * Characters
        * Images
    + Reply
    + Private Messages
- Notice
    + Notice Center
    + Email notice
- Seach
    + Users
    + Microblog
- Restful API
    + Fetch someone's microblogs
    + Post a microblog
    + Follow/Unfollow someone

## Userflow & Mockups

See files in /twitter-clone/design/

