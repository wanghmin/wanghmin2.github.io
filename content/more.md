---
title: About
date: '2018-06-28T00:00:00+01:00'
draft: false
share: false
commentable: false
editable: false

sections:
  
  - block: collection
    content:
      title: Recent Publications
      count: 6  
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '1'
      view: community/my_citation
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'    
---
