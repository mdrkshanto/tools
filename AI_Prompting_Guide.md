# RTCROS Prompting Guide

## RTCROS কী?

**RTCROS** হলো AI-কে একটি নির্দিষ্ট কাজ করানোর জন্য Prompt সাজানোর একটি কাঠামো:

- **R = Role** — AI কোন ভূমিকা পালন করবে
- **T = Task** — AI-কে কী কাজ করতে হবে
- **C = Context** — কাজটির প্রয়োজনীয় প্রেক্ষাপট ও তথ্য
- **R = Reasoning** — কী কী বিষয় বিবেচনা করে ফলাফল তৈরি করবে
- **O = Output Format** — ফলাফল কীভাবে দেখাবে
- **S = Stopping Condition** — কোথায় বা কখন উত্তর দেওয়া বন্ধ করবে

---

## 1. Blog Post Writer

Write a comprehensive blog post about **[TOPIC]**. Include an engaging introduction, well-structured main points, and a compelling conclusion. Make it SEO-friendly and engaging for readers.

---

## 2. Detailed Image Prompt

Create a detailed image of **[SUBJECT]**.

- **Style:** [STYLE]
- **Composition:** [COMPOSITION]
- **Lighting:** [LIGHTING]
- **Camera angle:** [ANGLE]
- **Quality:** High resolution, professional photography.

### Example Subject

**Tiger**

---

## 3. Video Script Creator

Create a video script for **[VIDEO_TYPE]** about **[TOPIC]**.

- **Duration:** [LENGTH]
- Include a strong hook in the first 5 seconds.
- Use engaging storytelling.
- Include a clear call-to-action.
- **Target audience:** [AUDIENCE]

---

## 4. Code Assistant

Help me with **[PROGRAMMING_LANGUAGE]** code for **[TASK]**.

Provide clean, well-commented code with explanations. Include error handling and follow best practices.

---

## 5. Social Media Manager

Create a **[PLATFORM]** post about **[TOPIC]**.

- Make it engaging.
- Include relevant hashtags.
- Optimize it for the platform's algorithm.
- **Target audience:** [AUDIENCE]
- **Call-to-action:** [CTA]

---

## 6. Business Strategy

Create a business strategy for **[BUSINESS_TYPE]**.

Include:

- Market analysis
- Target audience
- Competitive landscape
- Revenue model
- Growth strategy

Focus on **[SPECIFIC_AREA]**.

---

# GPT-5 Prompting Guide

OpenAI GPT-5 Prompting Guide:

https://cookbook.openai.com/examples/gpt-5/gpt-5_prompting_guide

---

# AI Image & Vector Marketplace Prompting

আমি একজন নতুন গ্রাফিক ডিজাইনার। আমি AI দিয়ে ইমেজ ও ভেক্টর বানিয়ে বিভিন্ন মার্কেটপ্লেসে সেল করতে চাই।

আমি চাই আমার ইমেজ তৈরির Prompt-গুলো **RTCROS** ফরম্যাটে সাজানো হবে।

## RTCROS Structure

```text
RTCROS

Role
Task
Context
Reasoning
Output Format
Stopping Condition
```

### Example Topic

**Subject: Frog Playing Hockey**

এই একই বিষয়ের উপর বিভিন্ন ধরনের ২০টি আলাদা RTCROS Prompt তৈরি করা যেতে পারে। প্রতিটি Prompt-এ Role, Task, Context, Reasoning, Output Format এবং Stopping Condition থাকবে।

---

# Cox's Bazar 3-Day Trip Prompt

আমি ৩ দিনের জন্য কক্সবাজার ঘুরতে যেতে চাই। এই ক্ষেত্রে RTCROS-এর প্রতিটি অংশে কী লিখলে সবচেয়ে ভালো Output পাওয়া যাবে?

## বাংলা Prompt

### Role

তুমি একজন অভিজ্ঞ ট্রাভেল প্ল্যানার এবং কক্সবাজারের লোকাল গাইড।

### Task

৩ দিনের জন্য কক্সবাজার ভ্রমণের একটি বিস্তারিত ট্যুর প্ল্যান তৈরি করো।

### Context

আমি আমার পরিবার নিয়ে ভ্রমণ করবো:

- ২ জন প্রাপ্তবয়স্ক
- ১ জন শিশু

আমরা আরামদায়ক ভ্রমণ পছন্দ করি।

আমরা:

- প্রাকৃতিক সৌন্দর্য উপভোগ করতে চাই।
- সমুদ্র সৈকত দেখতে চাই।
- লোকাল খাবার উপভোগ করতে চাই।

আমাদের বাজেট মাঝারি।

### Reasoning

প্রতিদিনের প্ল্যান এমনভাবে তৈরি করো যেন:

- দূরত্ব বিবেচনা করা হয়।
- যাতায়াতের সময় বিবেচনা করা হয়।
- ভ্রমণের ক্লান্তি বিবেচনা করা হয়।
- একই এলাকার জায়গাগুলো একই দিনে রাখা হয়।
- অপ্রয়োজনীয় তাড়াহুড়া এড়িয়ে চলা হয়।

### Output Format

দিন অনুযায়ী বুলেট পয়েন্ট আকারে ট্যুর প্ল্যান দেখাও।

প্রতিদিনের জন্য অন্তর্ভুক্ত করো:

- কোথায় যাবো
- কোন সময় সবচেয়ে ভালো
- খাবারের পরামর্শ
- গুরুত্বপূর্ণ টিপস

### Stopping Condition

৩ দিনের ট্যুর প্ল্যান শেষ হলে লেখা বন্ধ করো।

হোটেল বুকিং বা ওয়েবসাইট লিংক যোগ করো না।

---

## English Prompt

### Role

You are an experienced travel planner and local guide for Cox's Bazar, Bangladesh.

### Task

Create a detailed 3-day travel itinerary for Cox's Bazar.

### Context

I will be traveling with my family:

- 2 adults
- 1 child

We prefer a comfortable and relaxed travel experience.

We want to:

- Enjoy natural beauty.
- Visit and enjoy the beaches.
- Experience local food.

Our budget is moderate.

### Reasoning

Design each day's itinerary while considering:

- Distance between destinations.
- Travel time.
- Travel fatigue.
- Grouping destinations that are located in the same area on the same day.
- Avoiding unnecessary rushing.

### Output Format

Present the itinerary as bullet points organized by day.

For each day, include:

- Where to go
- The best time to visit
- Food recommendations
- Important tips

### Stopping Condition

Stop writing after completing the 3-day itinerary.

Do not include hotel booking information or website links.

---

# OpenAI Chat

https://platform.openai.com/chat

## GPT-5 Chat / Prompt Optimization

https://platform.openai.com/chat/edit?models=gpt-5&optimize=true

### Prompt

Help me to optimize this prompt.

---

# Gemini Prompting Guide

Google Gemini for Google Workspace Prompting Guide:

https://services.google.com/fh/files/misc/gemini-for-google-workspace-prompting-guide-101.pdf

---

# Kids' 3D Animation Video Project

আমি বাচ্চাদের জন্য অ্যানিমেশন ভিডিও বানাতে চাই।

আমার:

- **Target Audience:** America / United States
- **Video Style:** 3D Animation

এই বিষয়ে AI Prompt, Story, Character Design, Video Script, Scene Design এবং Content Strategy তৈরি করার জন্য RTCROS ফরম্যাট ব্যবহার করা যেতে পারে।
