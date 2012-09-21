# Spork::Minitest::Spec

This was made into a gem so specific patches to spork-minitest I've been using can be included in a testing framework gem that I use. (you cannot have a git repo as a dependency in a gem)

## What's different

minitest-rails uses a `minitest_helper.rb` file instead of a `test_helper.rb` file.
It includes fixes from nuxlli to support passing flags and minitest/pride

## Credit

semaperepelitsa - creating spork-minitest
nuxlli - patching spork-minitest to support passing flags and minitest/pride
