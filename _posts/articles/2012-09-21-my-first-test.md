---
layout: article
published: false
---

# Header 1
# Header 1
## Header 2
### Header 3

Text Annotations

*This text will be emphasized.*
**This text will be strong.**
Inline `code` in typewriter style

Links

[GitHub](http://github.com)

Images

![Alt text](/images/logo.png)

Blockquotes

William Zinser:

> Writing is thinking on paper. (no-more)

Unordered Lists

* Item 1
* Item 2
  * Item 2a
  * Item 2b

Ordered Lists

1. Item 1
1. Item 2
   1. Item 2a
   1. Item 2b
   
Code Blocks

Use 4 spaces indentation:

    function identity(x) {
      return x;
    }
    
    
   ![Setup Github Application](http://f.cl.ly/items/011W1c0D2N1I0B3m0731/Screen%20Shot%202012-05-31%20at%203.33.15%20PM.png)

3. Setup Gatekeeper.

   Follow the instructions here and fill in the information that is provided after registering a new Github Application.

4. Adjust `_config.yml`.
		auto: true
        server: true
       	oauth_client_id: your_oauth_client_id
       	gatekeeper_url: http://gatekeeper.example.com
       	exclude:
       - .gitignore
       - README.md    