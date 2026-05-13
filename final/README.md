# Project: Weight Loss and Wellness
**Description:** This project is a multi-page website about weight loss and wellness. The site will focus on helping visitors learn about healthy weight-loss support, body contouring options, and the benefits of personalized care in a welcoming spa environment.

**Key Facts/Inspiration:**
1. Many weight-loss spa websites use strong welcome sections with a motivational headline and a call to action.
2. A common section includes benefits of treatment, personalized plans, and consultation information.
3. Contact details, business hours, and clear service explanations help make the website feel professional and trustworthy.

## Page 1: Home
```text
Welcome to Your Weight Loss Journey

Taking the first step toward weight loss can feel overwhelming, but the right support can make a big difference. Our website is designed to help people explore weight-loss services, wellness support, and body goals in a simple and encouraging way. We want visitors to feel motivated, informed, and ready to begin their journey.

Weight loss is not only about appearance, but also about confidence, energy, and overall well-being. With personalized guidance, realistic goals, and supportive care, people can build healthier habits and work toward lasting results. This website highlights the value of affordable support and a positive environment.

What You Can Explore:
- Personalized weight-loss support
- Wellness and body contouring information
- Consultation and appointment details
- Healthy lifestyle motivation
- A welcoming and supportive experience
```

## Page 2: About About Our Weight Loss and Wellness Focus
```text
This website is centered on the idea that weight loss should feel supportive, realistic, and empowering. Everyone’s body and goals are different, so a successful wellness journey should include care that feels personal and encouraging. Our goal is to present information in a way that is simple, motivating, and useful for visitors.

We also want to show that weight-loss services can go beyond dieting alone. Many wellness-focused businesses combine guidance, body contouring services, and consultations to help clients work toward both health and confidence. By creating this site, I want to share content that feels professional, friendly, and easy to understand.

Our Main Focus Areas:
- Building confidence through wellness support
- Promoting realistic and healthy progress
- Explaining services in a clear way
- Encouraging visitors to take the first step
- Creating a positive and welcoming experience
```
## AI Session Link 
https://chatgpt.com/s/t_69bc5320e3008191818a3035140452a8

```
```
## Week 4: Design & Layout

### Colors

- Primary: #6FBF73
- Accent: #3fa136
- Background/Text: #FFFFFF

I chose green as my primary color because it represents health, growth, and wellness, which matches my website topic. I used natural green as an accent color to highlight sections without being too distracting. I chose white for the background to keep the design clean, simple, and easy to read.

### Fonts

Font Stack: Arial, Helvetica, sans-serif

I chose this font stack because it is clean, simple, and works on most devices. If Arial is not available, the browser will use Helvetica, and if that is not available, it will use a default sans-serif font.

```
```
## Week 5: Accessibility & Layout

I switched from pixels (px) to rem units because rem allows users to control the text size through their browser settings. This makes the website more accessible and easier to read for different users.

For the .cta-box, I used padding to create space inside the box so the text is not touching the border. I used margin to create space outside the box so it is separated from other content and centered on the page.
```
```
## Week 7 Engineering Notes

I used descendant selectors like `.hero-section h2` and `.cta-box h2` to target text inside specific sections of my website. The specificity score for these selectors is **0, 1, 1** because they include one class selector and one element selector.

This specificity is important because it is stronger than a global `h2` selector. It allows me to style headings only inside certain sections without affecting all headings on the page.
```
```
## Week 8 Engineering Notes

I chose 700px as my breakpoint because that is where the feature section started to feel cramped during the squish test. Below that size, the image and text work better stacked. Above that size, there is enough space for a two-column grid.

I removed the default margin and padding from the nav ul because browser styles add extra spacing that can make the header alignment look uneven. After removing those defaults, the logo and navigation links aligned better with Flexbox.

Nesting the media query inside the related selector keeps the responsive code close to the component it belongs to. This makes the CSS easier to read and easier to maintain instead of placing all media queries at the bottom of the file.

```
```
## Week 9 Sub Pages

I created two subpages called Motivation and Confidence and Healthy Nutrition. These pages are deep dives connected to topics already discussed on my main website pages.

The **Motivation and Confidence page** relates to the Wellness page because wellness journeys often require encouragement, consistency, and confidence-building. I linked this subpage through the "health"  text inside the wellness content so users can explore the topic in more detail.

The **Healthy Nutrition page** relates to the Tip page because healthy eating habits and balanced nutrition are important wellness tips. I linked this subpage through the “Healthy routines” text inside the tips content to create a deeper discussion about nutrition and healthy lifestyle choices.

Both subpages keep the same site-wide structure by using the same header, navigation, wrapper system, and footer design to maintain consistency across the website.
```

