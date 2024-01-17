---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<p id="pageViews">Loading (n) page views...</p>

<script async src="https://www.googletagmanager.com/gtag/js?id=G-EV2BPKWF3J"></script>

<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-EV2BPKWF3J');

  // Function to get page views
</script>
<script>
  function getPageViews() {
            gtag('event', 'page_view', {
                 'send_to': 'G-EV2BPKWF3J',
                 'event_callback': function() {
                    // Retrieve and display page views
                    var pageViews = gtag('get', 'G-EV2BPKWF3J', 'page_view');
                    document.getElementById('pageViews').innerText = 'Page Views: ' + pageViews;
                }
            });
        }
</script>
<!-- Call the function to get page views -->
<script>
    getPageViews();
</script>

I'm a PhD student of Artificial Intelligence in the School of Engineering Mathematics and Technology at the University of Bristol supervised by [Dr. Ryan McConville](https://ryanmcconville.com). I'm passionate about Open-Source Software, ~~Crypto~~, Yoga and Basketball.  If you have any questions that I can help with, please feel free to reach out via email at will.leeney@bristol.ac.uk or on LinkedIn. <a href="/files/leeney_will.pdf" download="leeney_will.pdf">Click here to download my CV.</a>  


My PhD thesis is currently titled: <b>How to Train and Benchmark Graph Neural Network Clustering Algorithms.</b> In this, I detail the capability of graphs as a data representation and the practical application of node clustering. I show the importance of hyperparameter optimisation to a benchmark in community detection compared to using default parameters. I propose metrics for quantifying the randomness in current machine learning algorithm comparisons, illustrating the problems with current evaluations. It is then demonstrated that completely unsupervised learning is possible with no comparison to any ground-truth labels and how this aids federated learning between multiple clients. 

Areas of Study
---
- `Unsupervised Learning`
- `GNNs`
- `Randomness in ML Benchmarking`
- `Federated Learning`
- `Community Detection`

I'm interested in AI as I believe we can improve the lives of all humans through practical machine learning. It's also pretty fun seeing sci-fi dreams come to life. The applications of my research can be to improve latent representations for enhancing search; to encode patient information for health care to predict drug treatment recommendation; to help detect fake news on social media networks; to find financial indicator signals for price prediction trading algorithms. 

Software Skills
--- 
- `python`
- `julia`
- `typescript`
- `latex`
- `git`
- `shell scripts`
- `C`
- `java`
- `html`
- `css`