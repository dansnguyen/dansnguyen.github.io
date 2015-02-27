---
layout: post
title:  "Dollars for Docs"
description: "A widescale collaborative investigation into the financial ties between doctors and drug companies"
content_type: News Application

lede_image:
  url: /images/posts/dollars-4-docs.header.jpg

thumbnail_url: /images/posts/dollars-4-docs.header.jpg

published_info:
  date: 2010-08-27
  site: ProPublica
  url: http://projects.propublica.org/docdollars
  logo_url: http://www.theweather.com/image.jpg

homepage_title: "Dollars for Docs: ProPublica"
homepage_position: 1
homepage_size: 2
---



This is my most well-known investigative news project, thanks to the hundreds of news and medical organizations that used our data
to produce their own reports, and of course, all the regular people curious about their own doctors. The popularity of Dollars for Docs 
spurred numerous changes in the industry, including 
Eli Lily [creating an independent screening process for its hired speakers](http://www.propublica.org/article/pharma-payments-to-doctors-with-sanctions) and 
medical schools [revising their conflict-of-interest policies](http://www.propublica.org/article/dollars-for-docs-sparks-policy-rewrite-at-colorado-teaching-hospitals).


{% include widgets/post_image.html src="/images/posts/dollars-4-docs.small.jpg" width="third"  pull="right"%}


One of the most satisfying aspects of D4D was how it started in my living room. I was writing a [blog post](http://danwin.com/2010/04/pfizer-web-scraping-for-journalists-part-4-pfizers-doctor-payments/)
about the practical benefits of programming for journalists, 
when I came across a New York Times article about how Pfizer, which was forced to disclose 
its payments to doctors, had published their data in an inconveniently designed website. The site was servicable, but 
its structure made it difficult to do even the most rudimentary analysis.

So I scraped Pfizer's listings and published the data and the code on my blog. Later that week, my colleague Charles Ornstein asked me
if it were possible to collect data for all the drug companies, and this is how ProPublica's biggest data project started.

Even with my colleagues Ornstein's and Tracy Weber's reporting expertise, I did not think the project would have a real impact. 
The political momentum to impose transparency on the companies was already in place, due to reporting by [The Times](http://www.nytimes.com/2007/03/21/us/21drug.html?pagewanted=all&_r=0) and [medical researchers](http://jama.jamanetwork.com/article.aspx?articleid=206127) in 2007.
However, I vastly underestimated the impact of making the data easy-to-find. Even if ProPublica was only revisiting the issue, 
I saw that a well-designed application could bring new angles to the story, through sheer magnitude and breadth of information.

People almost always overestimate the technical sophistication behind Dollars for Docs, especially since I wasn't a great programmer back then.
While it was time-consuming to collect the data and build 
the website, the hardest parts were the most pedantic. Such as: how to efficiently and, most importantly,
*accurately* fetch the data and pipe it to reporters, some of whom didn't know how to use spreadsheets. The biggest surprise for me of
Dollars for Docs was how great and basic the need was for reporters (and doctors) to better understand the nature of data. 
Not just how to process it in a technical way, but to fundamentally recognize its values (and limitations).

While researching the project, I spoke with Dr. Joseph Ross, who was the first to report on the [state and implications of this data in 2007](http://jama.jamanetwork.com/article.aspx?articleid=206127).
Dr. Ross told me that in Minnesota, this data had been public record but unexamined for nearly a decade, until he and his associates photocopied and
hand-entered the records into Access. By the time I started my project, the data was by comparison trivially easy to gather and analyze.
That I was able to make a big project out of it taught me to never assume that when something is public, that it also has been looked at.    

I ended up [writing a series of in-depth technical guides explaining](http://www.propublica.org/nerds/item/doc-dollars-guides-collecting-the-data) how I wrangled the data together: 

* [Using Google Refine to Clean Messy Data](http://www.propublica.org/nerds/item/using-google-refine-for-data-cleaning)
* [Reading Data from Flash Sites](http://www.propublica.org/nerds/item/reading-flash-data)
* [Turning PDFs to Text](http://www.propublica.org/nerds/item/turning-pdfs-to-text-doc-dollars-guide)
* [Scraping Data from HTML](http://www.propublica.org/nerds/item/scraping-websites)
* [Getting Text Out of an Image-Only PDF](http://www.propublica.org/nerds/item/doc-dollars-guides-collecting-the-data)
