# -*- mode: ruby; coding: utf-8; -*-

site :opscode

metadata

cookbook 'java', git: 'https://github.com/socrata-cookbooks/java'
cookbook 'ark', '0.7.0'
cookbook 'tomcat', git: 'https://github.com/cantenesse/tomcat', branch: 'ssl-enable'
cookbook 'application_java', git: 'https://github.com/jamiely/application_java'
cookbook 'mongodb', git: 'https://github.com/edelight/chef-mongodb'
cookbook 'chef-solo-search', git: 'https://github.com/edelight/chef-solo-search.git', tag: '0.5.1'

group :integration do
  cookbook 'apt', '~> 2.0'
end
