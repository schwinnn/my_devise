Blog: A platform for sharing blogs
=======



Blog, you know, a platform for sharing blog.
Site url: [http://www.blog-eye.com/](http://www.blog-eye.com/)

## How to Install

Make sure mysql already started.
```bash
git clone git@github.com:agilejzl/blog-eye.git
cd blog-eye
ruby setup.rb # A ruby script to make project RTF

# Then change config at database.yml and settings.yml
RAILS_ENV=development rails s
# start delayed_job for async sending email and uploading photo
RAILS_ENV=development bin/delayed_job start
```
