# Debug Politics Website

debugpolitics.com

## Development Environment

Should be _super easy_. This project is set up to use [Middleman], a popular
static-site generator (like Jekyll) written in Ruby.

1. `bundle install`
2. `bundle exec middleman server`
3. Visit `http://127.0.0.1:4567/` in your browser. Changes you make to in
   `source` will automatically rebuild and appear in your browser.

## Development Workflow

This project is set up with continuous deployment. All branches are
automatically deployed to Heroku, `master` representing production.

1. Cut a branch, call it whatever you want (feature nickname preferable).
2. Code, commit, repeat.
3. Push your branch.
4. Make a PR.
5. Your PR should automatically deploy to a temporary Heroku app, which you can
   send around for approval.

When you're ready to deploy to production, you just need someone to review the
PR. When you merge to production, voilà, the changes will be live.

[Middleman]: https://middlemanapp.com/
