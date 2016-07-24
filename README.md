# workspace_joa

My repo for working on the [Joy of Automation](https://www.youtube.com/playlist?list=PL11cZfNdwNyORJfIYA8t07PRMchyDXIjq) webinar series by CHEF

### Episode 5
-----------
Things I didn't know about before working through episode 5
* [let](https://www.relishapp.com/rspec/rspec-core/v/3-5/docs/helper-methods/let-and-let) - In this context it was used to define an array of packages to check that were installed
* [shared_examples](https://www.relishapp.com/rspec/rspec-core/v/3-5/docs/example-groups/shared-examples) - We used shared_examples to reduce duplicated code for checking packages that were installed, ultimately ended up in the spec_helper.rb
* [shared_context](https://www.relishapp.com/rspec/rspec-core/v/ 3-5/docs/example-groups/shared-context) - Similar on how ended up using shared_examples, this allowed us to set up similar contexts for each system type without much code duplication.
* Breaking different contexts out into new files
