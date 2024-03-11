* template
  ```
  jekyll new . --force
  ```
* jekyll seo
  *  install
      ```
      gem install 'jekyll-seo-tag'
  
      ```
  *  add in `_config.yml`
      ```
      plugins:
        - jekyll-seo-tag
  
      ```
  *  add in `<head>` tag
      ```
      {% seo %}
  
      ```
