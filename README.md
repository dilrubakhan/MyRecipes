# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions


***To avoid error---- ActionView::Template::Error: Permission denied @ rb_file_s_rename -

In test/test_helper.rb, commented out the following line:

# parallelize(workers: :number_of_processors, with: :threads)
no parallell testing, no problem

***end



* ...