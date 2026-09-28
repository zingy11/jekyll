# jekyll
# step1
gem install jekyll bundler  
jekyll --version  
bundle --version  
bundle init  

edit gemfile so it contains:  
source "https://rubygems.org"  
gem "jekyll"  

then:  
bundle install  
mkdir docs
# step2
touch docs/index.md  
put the stuff in:(index.md)  
jekyll --version  
jekyll serve --source docs  

# step3
added the docs/index2.md to showcase styling of (https://jekyllrb.com/docs/)  
jekyll serve --source docs