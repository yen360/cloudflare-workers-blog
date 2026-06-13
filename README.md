> This is a blog application that runs on Cloudflare Workers, using Cloudflare KV as its database, with no other dependencies.
It combines the speed of a static blog with the flexibility of a dynamic blog — easy to set up, hassle-free, and very stable.
Demo: [https://blog.gezhong.vip](https://blog.gezhong.vip "cf-blog demo site")

### TG discussion group: [@CloudflareBlog](https://t.me/cloudflareblog "")
# Key Features
* Uses the KV provided by Workers as the database
* Uses Cloudflare's HTML caching to reduce KV reads/writes
* All HTML pages are cached, achieving static-blog speed
* Uses KV as the database, achieving WordPress-level flexibility
* The admin panel uses Markdown syntax — quick and convenient
* One-click publish (page rebuild + cache purge)

# Capacity
 * KV is essentially never a bottleneck, since caching keeps reads/writes minimal
 * The only bottleneck is the Workers daily request limit of 100k, which can handle roughly 20,000 IPs/day
 * Article count: with 1 GB of storage, tens of thousands of articles are no problem

# Deployment Steps
  Not having a live preview here is really painful; a series of gotchas will gradually be documented on the blog — stay tuned at [https://blog.gezhong.vip](https://blog.gezhong.vip "")

# Changelog

> [Continuously updated at https://blog.gezhong.vip/article/009000/update-log.html](https://blog.gezhong.vip/article/009000/update-log.html "Changelog")
  
## Latest Updates (2020-12-31)
* 2020-12-31: Added sitemap.xml
* 2020-12-24: This update mainly targets SEO and read counts, along with various detail optimizations




### Frontend demo: [https://blog.gezhong.vip](https://blog.gezhong.vip "demo site")
![](https://s3.ax1x.com/2020/12/22/rrP81S.png)

### Backend demo:
![](https://s3.ax1x.com/2020/12/22/rrAWrD.png)

## Donate

If you feel this project has helped you, please consider supporting the author

* [Donate](https://www.paypal.com/paypalme/stevie90)  
