# my_website

# This is my website

git push
[build] 
  publish = "public"
  command = "hugo"

[build.environment]
  HUGO_VERSION = "0.83.1"
  HUGO_ENABLEGITINFO = "true"

[context.production.environment]
  HUGO_ENV = "production"
  
[context.branch-deploy.environment]
  HUGO_VERSION = "0.83.1"

[context.deploy-preview.environment]
  HUGO_VERSION = "0.83.1"  
  