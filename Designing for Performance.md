# Designing for Performance
## Lara Hogan

* users expect sites to load in 2 seconds
* in 3 seconds, 40% of users will abandon your site
* blurring images actually effect image file size
* gifs only work with horizontal redundancy when blending

```
img srcset=“small medium large” sizes=“(max-width: 480px) 75vw”
```

```
picture
	source type=“image/svg”
	img
/picture
```

* only @import done weights you absolute need, IE6-8 automatically downloads all font-face declarations
* Only large screens should download font file, don’t make the mobile users download your fonts
* rename non-semantic elements
* make performance part of everyone’s workflow
* user a mobile-first workflow
* Create a performance budget. Measure/Goal/Notes, set these as milestones to hit and maintain during development
* Be deliberate about loading assets like images, fonts, and javascript files - they can be single points of failure
* system font for body copy is a big typographic win
* self-host videos and load it async
* compromise
* A/B test to measure aesthetics vs. performance impact
* make it easy for non-developers to do performance
* help people feel your site’s performance
* [Designing for Performance](designingforperformance.com)