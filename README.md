# JAS-WEB-Laravel-Docs

A brief description and analysis that went into building the site jayaramassociates.com

Followed Build Process 

## To build 
```mermaid

mindmap
    JayaramAssocaites
        SEO
            sitemap
            Dynamic Page SEO
        Blog
            Admin 
                secure login
                CRUD
                Latex support editing
           customer paginated view
        GST
            Scrapping
                cleaning
                json to flat db
            data Inegration
                view Html
                pdf download
        Deployment
        Design
```
A dynamic modern website that garners attention and addes value for the targeted demografic viewer's time.

## Scrapping

>In this World's wide waters we the scrappers are the fishermen, casting our nets and to hope catch a whale , but often forget the tide it brings 

We need tons of indian GST information acts,rules,notification,circulars,and forms as they are released and to be accessible to the end use in our website, as a knowledge base.

So adhering to the robots.txt file from the source websites

```mermaid
graph LR

    id1[(Database)]-->Web_Integration
    Selenium_network_modification-->json@{ shape: procs, label: "JSON"}
    json-->flat@{ shape: das, label: "Flattenning" }
    flat --> id1

```

## Blog

>Made by Web Artisan for Web Artisans
>   -laravel

the beauty of MVC architecture crafted to perfection by the simplicity of laravel, writeen in php. I was convinced that this frame work is the go to.

```mermaid
graph 
    User("😁 User")--no login view-->blog(blog)
    Admin("🐱‍👤 Admin")--secured crud-->blog
```

for login and user session tracking , no worried laravel doe it all for you inbuilt in controller in