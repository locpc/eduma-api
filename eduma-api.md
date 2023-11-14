## EDUMA APIS

---

<details>
 <summary><code>POST</code> <code><b>/wp-json/learnpress/v1/token</b></code> <code>(login)</code></summary>

##### Parameters

> | name     | type     | data type | description |
> | -------- | -------- | --------- | ----------- |
> | username | required | string    | N/A         |
> | password | required | string    | N/A         |

##### Responses

```json
{
	"token": "eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJodHRwczpcL1wvdGVzdC50aGltcHJlc3MuY29tIiwiaWF0IjoxNjk5OTQ4NTYzLCJuYmYiOjE2OTk5NDg1NjMsImV4cCI6MTcwMDU1MzM2MywiZGF0YSI6eyJ1c2VyIjp7ImlkIjoiMjUzNSJ9fX0.-ing0u-9mwzKz8iDzQ8axfigNFIlMxWUemNZcfaU2OI",
	"user_display_name": "locpc",
	"user_email": "pcloc101099@gmail.com",
	"user_id": "2535",
	"user_login": "locpc"
}
```

</details>

---

<details>
 <summary><code>POST</code> <code><b>/wp-json/learnpress/v1/token/register</b></code> <code>(register)</code></summary>

##### Parameters

> | name             | type     | data type | description |
> | ---------------- | -------- | --------- | ----------- |
> | email            | required | string    | N/A         |
> | username         | required | string    | N/A         |
> | password         | required | string    | N/A         |
> | confirm_password | required | string    | N/A         |

##### Responses

```json
{
	"code": "registration-error-email-exists",
	"data": { "status": 403 },
	"message": "An account is already registered with your email address."
}
```

</details>

---

<details>
 <summary><code>GET</code> <code><b>/wp-json/learnpress/v1/courses</b></code> <code>(course)</code></summary>

##### Parameters

> | name     | type     | data type                                                                                                                                   | description |
> | -------- | -------- | ------------------------------------------------------------------------------------------------------------------------------------------- | ----------- |
> | page     | required | string                                                                                                                                      | N/A         |
> | per_page | required | string                                                                                                                                      | N/A         |
> | learned  | required | true                                                                                                                                        | N/A         |
> | optimize | required | 'sections,on_sale,can_finish,can_retake,ratake_count,rataken,rating,price,origin_price,sale_price,tags,count_students,instructor,meta_data' | N/A         |

##### Responses

```json
[{"categories": [[Object], [Object]], "content": "<h4>COURSE DESCRIPTION</h4>
<p><span class=\"style-scope yt-formatted-string\" dir=\"auto\">A series of Videos from ThimPress, give you a detailed tutorial to create an LMS Website with LearnPress &#8211; LMS &amp; Education WordPress Plugin.</span></p>
<p><iframe loading=\"lazy\" title=\"LearnPress 4.0 Beta 2\" width=\"750\" height=\"422\" src=\"https://www.youtube.com/embed/5jdAYTjj3LM?feature=oembed\" frameborder=\"0\" allow=\"accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share\" allowfullscreen></iframe></p>
<p>This course is a detailed and easy tutorial to get you all setup and going with the use of <a href=\"https://wordpress.org/plugins/learnpress/\" target=\"_blank\" rel=\"noopener\"><strong>LearnPress LMS Plugin</strong></a>. It is a free and simple plugin to help you create an <strong>Online Courses Website</strong> step by step. The tutorial guides you through the configuration of the plugin, creation of Courses, Lessons, Quizzes, and finally guides you on how to boost up your Website with <a href=\"https://thimpress.com/wordpress/plugins/learnpress/?utm_source=Eduma&amp;utm_medium=Course&amp;utm_campaign=LMSWebsite\" target=\"_blank\" rel=\"noopener\"><strong>Premium LearnPress Add-ons</strong></a> brought to you by ThimPress (creator of LearnPress). It also shows how you could configure additional items like the course layouts and featured images.</p>
<h4>CERTIFICATION</h4>
<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry’s standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.</p>
<h4>LEARNING OUTCOMES</h4>
<ul class=\"thim-list-content\">
<li>Over 37 lectures and 55.5 hours of content!</li>
<li>Testing Training Included.</li>
<li>Learn Software Testing and Automation basics from a professional trainer from your own desk.</li>
<li>Information packed practical training starting from basics to advanced testing techniques.</li>
<li>Best suitable for beginners to advanced level users and who learn faster when demonstrated.</li>
<li>Course content designed by considering current software testing technology and the job market.</li>
<li>Practical assignments at the end of every session.</li>
<li>Practical learning experience with live project work and examples.</li>
</ul>
", "course_data": {"end_time": null, "expiration_time": "2023-11-14T04:17:28", "graduation": "in-progress", "result": [Object], "start_time": "2023-11-14T04:07:28", "status": "enrolled"}, "date_created": "2022-12-16T07:17:54", "date_created_gmt": "2022-12-16T07:17:54", "date_modified": "2023-06-26T11:06:23", "date_modified_gmt": "2023-06-26T11:06:23", "duration": "10 minutes", "excerpt": "", "id": 7178, "image": "https://test.thimpress.com/wp-content/uploads/2022/12/introduction-learnpress-lms-plugin.jpg", "meta_data": {"_lp_allow_course_repurchase": "no", "_lp_block_expire_duration": "no", "_lp_block_finished": "yes", "_lp_course_author": "1", "_lp_course_material": "", "_lp_course_repurchase_option": "reset", "_lp_course_result": "evaluate_lesson", "_lp_duration": "10 minute", "_lp_external_link_buy_course": "", "_lp_faqs": [Array], "_lp_featured": "no", "_lp_featured_review": "", "_lp_has_finish": "yes", "_lp_key_features": [Array], "_lp_level": "beginner", "_lp_max_students": "10000", "_lp_no_required_enroll": "no", "_lp_passing_condition": "80", "_lp_regular_price": "", "_lp_requirements": [Array], "_lp_retake_count": "12", "_lp_sale_end": "", "_lp_sale_price": "", "_lp_sale_start": "", "_lp_students": "273", "_lp_target_audiences": [Array]}, "name": "Introduction LearnPress - LMS plugin", "origin_price_rendered": "$0.00", "permalink": "https://test.thimpress.com/courses/introduction-learnpress-lms-plugin/", "price_rendered": "Free", "sale_price_rendered": "$0.00", "slug": "introduction-learnpress-lms-plugin", "status": "publish"}, {"categories": [[Object]], "content": "<p><span class=\"style-scope yt-formatted-string\" dir=\"auto\">A series of Videos from ThimPress, give you a detailed tutorial to create an LMS Website with LearnPress &#8211; LMS &amp; Education WordPress Plugin.</span></p>
<p>This course is a detailed and easy tutorial to get you all setup and going with the use of <a href=\"https://wordpress.org/plugins/learnpress/\" target=\"_blank\" rel=\"noopener\"><strong>LearnPress LMS Plugin</strong></a>. It is a free and simple plugin to help you create an <strong>Online Courses Website</strong> step by step. The tutorial guides you through the configuration of the plugin, creation of Courses, Lessons, Quizzes, and finally guides you on how to boost up your Website with <a href=\"https://thimpress.com/wordpress/plugins/learnpress/?utm_source=Eduma&amp;utm_medium=Course&amp;utm_campaign=LMSWebsite\" target=\"_blank\" rel=\"noopener\"><strong>Premium LearnPress Add-ons</strong></a> brought to you by ThimPress (creator of LearnPress). It also shows how you could configure additional items like the course layouts and featured images.</p>
", "course_data": {"end_time": null, "expiration_time": "2024-01-23T04:11:37", "graduation": "in-progress", "result": [Object], "start_time": "2023-11-14T04:11:37", "status": "enrolled"}, "date_created": "2022-12-16T04:10:35", "date_created_gmt": "2022-12-16T04:10:35", "date_modified": "2023-06-26T08:13:31", "date_modified_gmt": "2023-06-26T08:13:31", "duration": "10 weeks", "excerpt": "", "id": 7138, "image": "https://test.thimpress.com/wp-content/uploads/2022/12/admin-ajax.jpeg", "meta_data": {"_lp_allow_course_repurchase": "no", "_lp_block_expire_duration": "no", "_lp_block_finished": "yes", "_lp_course_author": "1", "_lp_course_material": "", "_lp_course_repurchase_option": "reset", "_lp_course_result": "evaluate_lesson", "_lp_duration": "10 week", "_lp_external_link_buy_course": "", "_lp_faqs": [Array], "_lp_featured": "yes", "_lp_featured_review": "", "_lp_has_finish": "yes", "_lp_key_features": [Array], "_lp_level": "", "_lp_max_students": "0", "_lp_no_required_enroll": "no", "_lp_passing_condition": "80", "_lp_regular_price": "", "_lp_requirements": [Array], "_lp_retake_count": "1", "_lp_sale_end": "", "_lp_sale_price": "", "_lp_sale_start": "", "_lp_students": "50", "_lp_target_audiences": [Array]}, "name": "Create an LMS Website with LearnPress", "origin_price_rendered": "$0.00", "permalink": "https://test.thimpress.com/courses/create-an-lms-website-with-learnpress/", "price_rendered": "Free", "sale_price_rendered": "$0.00", "slug": "create-an-lms-website-with-learnpress", "status": "publish"}, {"categories": [[Object]], "content": "<h4>COURSE DESCRIPTION</h4>
<p>jQuery Mobile framework takes the &#8220;write less, do more&#8221; mantra to the next level: Instead of writing unique applications for each mobile device or OS, the jQuery mobile framework allows you to design a single highly-branded responsive web site or application that will work on all popular smartphone, tablet, and desktop platforms.</p>
<p>The purpose of jQuery is to make it much easier to use JavaScript on your website.</p>
<h4>What You Should Already Know</h4>
<p>Before you start studying jQuery, you should have a basic knowledge of:</p>
<ul>
<li>HTML</li>
<li>CSS</li>
<li>JavaScript</li>
</ul>
<p>If you want to study these subjects first, find the tutorials on our Home page.</p>
<h4>Why jQuery?</h4>
<p>There are lots of other JavaScript frameworks out there, but jQuery seems to be the most popular, and also the most extendable.</p>
<p>Many of the biggest companies on the Web use jQuery, such as:</p>
<ul>
<li>Google</li>
<li>Microsoft</li>
<li>IBM</li>
<li>Netflix</li>
</ul>
<h4>LEARNING OUTCOMES</h4>
<ul class=\"thim-list-content\">
<li>Over 37 lectures and 55.5 hours of content!</li>
<li>LIVE PROJECT End to End Software Testing Training Included.</li>
<li>Learn Software Testing and Automation basics from a professional trainer from your own desk.</li>
<li>Information packed practical training starting from basics to advanced testing techniques.</li>
<li>Best suitable for beginners to advanced level users and who learn faster when demonstrated.</li>
<li>Course content designed by considering current software testing technology and the job market.</li>
<li>Practical assignments at the end of every session.</li>
<li>Practical learning experience with live project work and examples.</li>
</ul>
", "course_data": {"end_time": "2023-11-13T03:46:14", "expiration_time": "2023-11-15T15:45:40", "graduation": "passed", "result": [Object], "start_time": "2023-11-13T03:45:40", "status": "finished"}, "date_created": "2015-12-16T09:21:10", "date_created_gmt": "2015-12-16T09:21:10", "date_modified": "2022-08-04T07:46:28", "date_modified_gmt": "2022-08-04T07:46:28", "duration": "60 hours", "excerpt": "The jQuery team knows all about cross-browser issues, and they have written this knowledge into the jQuery library. jQuery will run exactly the same in all major browsers, including Internet Explorer 6     ", "id": 4271, "image": "https://test.thimpress.com/wp-content/uploads/2015/12/unsplash_Oalh2MojUuk.png", "meta_data": {"_lp_allow_course_repurchase": "no", "_lp_block_expire_duration": "no", "_lp_block_finished": "no", "_lp_course_author": "4", "_lp_course_material": "", "_lp_course_repurchase_option": "reset", "_lp_course_result": "evaluate_lesson", "_lp_duration": "60 hour", "_lp_external_link_buy_course": "", "_lp_faqs": [Array], "_lp_featured": "no", "_lp_featured_review": "", "_lp_has_finish": "yes", "_lp_key_features": [Array], "_lp_level": "", "_lp_max_students": "1000", "_lp_no_required_enroll": "no", "_lp_passing_condition": "50", "_lp_regular_price": "25", "_lp_requirements": [Array], "_lp_retake_count": "0", "_lp_sale_end": "", "_lp_sale_price": "0", "_lp_sale_start": "", "_lp_students": "32", "_lp_target_audiences": [Array]}, "name": "Learning jQuery Mobile for Beginners", "origin_price_rendered": "$25.00", "permalink": "https://test.thimpress.com/courses/learning-jquery-mobile-for-beginners/", "price_rendered": "Free", "sale_price_rendered": "$0.00", "slug": "learning-jquery-mobile-for-beginners", "status": "publish"}, {"categories": [[Object]], "content": "<h4></h4>
<h4>COURSE DESCRIPTION</h4>
<p>LESS is a CSS pre-processor that enables customizable, manageable and reusable style sheet for website. LESS is a dynamic style sheet language that extends the capability of CSS. LESS is also cross browser friendly.</p>
<p>CSS Preprocessor is a scripting language that extends CSS and gets compiled into regular CSS syntax, so that it can be read by your web browser. It provides functionalities like <i>variables</i>, <i>functions</i>, <i>mixins</i> and <i>operations</i> that allow you to build dynamic CSS.</p>
<h4>Why LESS?</h4>
<p>Let us now understand why do we use LESS.</p>
<ul class=\"list\">
<li>LESS supports creating cleaner, cross-browser friendly CSS faster and easier.</li>
<li>LESS is designed in JavaScript and also created to be used in <i>live</i>, which compiles faster than other CSS pre-processors.</li>
<li>LESS keeps your code in modular way which is really important by making it readable and easily changeable.</li>
<li>Faster maintenance can be achieved by the use of LESS <i>variables</i>.</li>
</ul>
<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry&#8217;s standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.</p>
<h4>LEARNING OUTCOMES</h4>
<ul class=\"thim-list-content\">
<li>Over 37 lectures and 55.5 hours of content!</li>
<li>LIVE PROJECT End to End Software Testing Training Included.</li>
<li>Learn Software Testing and Automation basics from a professional trainer from your own desk.</li>
<li>Information packed practical training starting from basics to advanced testing techniques.</li>
<li>Best suitable for beginners to advanced level users and who learn faster when demonstrated.</li>
<li>Course content designed by considering current software testing technology and the job market.</li>
<li>Practical assignments at the end of every session.</li>
<li>Practical learning experience with live project work and examples.</li>
</ul>
", "course_data": {"end_time": "2023-11-14T04:21:26", "expiration_time": "2023-11-14T16:55:44", "graduation": "passed", "result": [Object], "start_time": "2023-11-13T10:55:44", "status": "finished"}, "date_created": "2015-06-13T09:57:39", "date_created_gmt": "2015-06-13T09:57:39", "date_modified": "2022-06-13T04:52:48", "date_modified_gmt": "2022-06-13T04:52:48", "duration": "30 hours", "excerpt": "Less is a CSS pre-processor, meaning that it extends the CSS language, adding features that allow variables, mixins, functions and many other techniques that allow you to make CSS that is more maintainable, themable and extendable.       ", "id": 4199, "image": "https://test.thimpress.com/wp-content/uploads/2015/12/Rectangle-285-7.png", "meta_data": {"_lp_allow_course_repurchase": "no", "_lp_block_expire_duration": "no", "_lp_block_finished": "no", "_lp_course_author": "1", "_lp_course_material": "", "_lp_course_repurchase_option": "reset", "_lp_course_result": "evaluate_lesson", "_lp_duration": "30 hour", "_lp_external_link_buy_course": "", "_lp_faqs": [Array], "_lp_featured": "no", "_lp_featured_review": "", "_lp_has_finish": "yes", "_lp_key_features": [Array], "_lp_level": [Array], "_lp_max_students": "1000", "_lp_no_required_enroll": "no", "_lp_passing_condition": "50", "_lp_regular_price": "0", "_lp_requirements": [Array], "_lp_retake_count": "0", "_lp_sale_end": "", "_lp_sale_price": "", "_lp_sale_start": "", "_lp_students": "34", "_lp_target_audiences": [Array]}, "name": "Getting Started with LESS", "origin_price_rendered": "$0.00", "permalink": "https://test.thimpress.com/courses/getting-started-with-less-beginner-crash/", "price_rendered": "Free", "sale_price_rendered": "$0.00", "slug": "getting-started-with-less-beginner-crash", "status": "publish"}]
```

</details>

---

<details>
 <summary><code>GET</code> <code><b>/wp-json/learnpress/v1/courses/${id}</b></code> <code>(courseDetail)</code></summary>

##### Parameters

##### Responses

```json
{"can_finish": false, "can_retake": false, "categories": [{"id": 8, "name": "CSS", "slug": "css"}, {"id": 25, "name": "Teaching Online", "slug": "teaching-online"}], "content": "<h4>COURSE DESCRIPTION</h4>
<p><span class=\"style-scope yt-formatted-string\" dir=\"auto\">A series of Videos from ThimPress, give you a detailed tutorial to create an LMS Website with LearnPress &#8211; LMS &amp; Education WordPress Plugin.</span></p>
<p><iframe loading=\"lazy\" title=\"LearnPress 4.0 Beta 2\" width=\"750\" height=\"422\" src=\"https://www.youtube.com/embed/5jdAYTjj3LM?feature=oembed\" frameborder=\"0\" allow=\"accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share\" allowfullscreen></iframe></p>
<p>This course is a detailed and easy tutorial to get you all setup and going with the use of <a href=\"https://wordpress.org/plugins/learnpress/\" target=\"_blank\" rel=\"noopener\"><strong>LearnPress LMS Plugin</strong></a>. It is a free and simple plugin to help you create an <strong>Online Courses Website</strong> step by step. The tutorial guides you through the configuration of the plugin, creation of Courses, Lessons, Quizzes, and finally guides you on how to boost up your Website with <a href=\"https://thimpress.com/wordpress/plugins/learnpress/?utm_source=Eduma&amp;utm_medium=Course&amp;utm_campaign=LMSWebsite\" target=\"_blank\" rel=\"noopener\"><strong>Premium LearnPress Add-ons</strong></a> brought to you by ThimPress (creator of LearnPress). It also shows how you could configure additional items like the course layouts and featured images.</p>
<h4>CERTIFICATION</h4>
<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry’s standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.</p>
<h4>LEARNING OUTCOMES</h4>
<ul class=\"thim-list-content\">
<li>Over 37 lectures and 55.5 hours of content!</li>
<li>Testing Training Included.</li>
<li>Learn Software Testing and Automation basics from a professional trainer from your own desk.</li>
<li>Information packed practical training starting from basics to advanced testing techniques.</li>
<li>Best suitable for beginners to advanced level users and who learn faster when demonstrated.</li>
<li>Course content designed by considering current software testing technology and the job market.</li>
<li>Practical assignments at the end of every session.</li>
<li>Practical learning experience with live project work and examples.</li>
</ul>
", "count_students": 337, "course_data": {"end_time": null, "expiration_time": "2023-11-14T04:17:28", "graduation": "in-progress", "result": {"completed_items": 0, "count_items": 12, "evaluate_type": "evaluate_lesson", "items": [Object], "pass": 0, "result": 0}, "start_time": "2023-11-14T04:07:28", "status": "enrolled"}, "date_created": "2022-12-16T07:17:54", "date_created_gmt": "2022-12-16T07:17:54", "date_modified": "2023-06-26T11:06:23", "date_modified_gmt": "2023-06-26T11:06:23", "duration": "10 minutes", "excerpt": "", "id": 7178, "image": "https://test.thimpress.com/wp-content/uploads/2022/12/introduction-learnpress-lms-plugin.jpg", "instructor": {"avatar": false, "description": "For React Native, we decided to use web paradigm for this where you can nest text to achieve the same effect.", "id": 1, "name": "pensive-tesla", "social": {"facebook": "https://mail.google.com/mail/u/2/#inbox", "linkedin": "https://mail.google.com/mail/u/2/#inbox", "twitter": "https://mail.google.com/mail/u/2/#inbox", "youtube": "https://mail.google.com/mail/u/2/#inbox"}}, "meta_data": {"_lp_allow_course_repurchase": "no", "_lp_block_expire_duration": "no", "_lp_block_finished": "yes", "_lp_course_author": "1", "_lp_course_material": "", "_lp_course_repurchase_option": "reset", "_lp_course_result": "evaluate_lesson", "_lp_duration": "10 minute", "_lp_external_link_buy_course": "", "_lp_faqs": [], "_lp_featured": "no", "_lp_featured_review": "", "_lp_has_finish": "yes", "_lp_key_features": [], "_lp_level": "beginner", "_lp_max_students": "10000", "_lp_no_required_enroll": "no", "_lp_passing_condition": "80", "_lp_regular_price": "", "_lp_requirements": [], "_lp_retake_count": "12", "_lp_sale_end": "", "_lp_sale_price": "", "_lp_sale_start": "", "_lp_students": "273", "_lp_target_audiences": []}, "name": "Introduction LearnPress - LMS plugin", "on_sale": false, "origin_price": 0, "origin_price_rendered": "$0.00", "permalink": "https://test.thimpress.com/courses/introduction-learnpress-lms-plugin/", "price": 0, "price_rendered": "Free", "ratake_count": 12, "rataken": 1, "rating": 4.6, "sale_price": 0, "sale_price_rendered": "$0.00", "sections": [{"course_id": 7178, "description": "", "id": 158, "items": [Array], "order": "1", "percent": 0, "title": "Zoom Meeting"}, {"course_id": 7178, "description": "", "id": 159, "items": [Array], "order": "2", "percent": 0, "title": "LearnPress Interactive Content"}, {"course_id": 7178, "description": "", "id": 160, "items": [Array], "order": "3", "percent": 0, "title": "LearnPress Getting Started"}], "slug": "introduction-learnpress-lms-plugin", "status": "publish", "tags": []}
```

</details>

---

<details>
 <summary><code>GET</code> <code><b>/wp-json/learnpress/v1/lessons/${id}</b></code> <code>(lessonWithId)</code></summary>

##### Parameters

##### Responses

```json
{"assigned": {"course": {"author": "1", "content": "<h4>COURSE DESCRIPTION</h4>
<span class=\"style-scope yt-formatted-string\" dir=\"auto\">A series of Videos from ThimPress, give you a detailed tutorial to create an LMS Website with LearnPress - LMS &amp; Education WordPress Plugin.</span>

https://www.youtube.com/watch?v=5jdAYTjj3LM

This course is a detailed and easy tutorial to get you all setup and going with the use of <a href=\"https://wordpress.org/plugins/learnpress/\" target=\"_blank\" rel=\"noopener\"><strong>LearnPress LMS Plugin</strong></a>. It is a free and simple plugin to help you create an <strong>Online Courses Website</strong> step by step. The tutorial guides you through the configuration of the plugin, creation of Courses, Lessons, Quizzes, and finally guides you on how to boost up your Website with <a href=\"https://thimpress.com/wordpress/plugins/learnpress/?utm_source=Eduma&amp;utm_medium=Course&amp;utm_campaign=LMSWebsite\" target=\"_blank\" rel=\"noopener\"><strong>Premium LearnPress Add-ons</strong></a> brought to you by ThimPress (creator of LearnPress). It also shows how you could configure additional items like the course layouts and featured images.
<h4>CERTIFICATION</h4>
Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry’s standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.
<h4>LEARNING OUTCOMES</h4>
<ul class=\"thim-list-content\">
        <li>Over 37 lectures and 55.5 hours of content!</li>
        <li>Testing Training Included.</li>
        <li>Learn Software Testing and Automation basics from a professional trainer from your own desk.</li>
        <li>Information packed practical training starting from basics to advanced testing techniques.</li>
        <li>Best suitable for beginners to advanced level users and who learn faster when demonstrated.</li>
        <li>Course content designed by considering current software testing technology and the job market.</li>
        <li>Practical assignments at the end of every session.</li>
        <li>Practical learning experience with live project work and examples.</li>
</ul>", "id": "7178", "slug": "introduction-learnpress-lms-plugin", "title": "Introduction LearnPress - LMS plugin"}}, "can_finish_course": false, "content": "<p>[zoom_api_link meeting_id=&#8221;71688919185&#8243; link_only=&#8221;no&#8221;]</p>
", "date_created": "2022-12-16T07:19:00", "date_created_gmt": "2022-12-16T07:19:00", "date_modified": "2022-12-16T07:19:24", "date_modified_gmt": "2022-12-16T07:19:24", "duration": "Lifetime", "excerpt": "", "id": 7180, "meta_data": {"_lp_duration": "0 minute", "_lp_preview": "yes"}, "name": "Zoom – Study Online", "permalink": "https://test.thimpress.com/courses/introduction-learnpress-lms-plugin/lessons/zoom-study-online-2/", "results": {"status": ""}, "slug": "zoom-study-online-2", "status": "publish", "video_intro": ""}
```

</details>

---

<details>
 <summary><code>POST</code> <code><b>/wp-json/learnpress/v1/courses/enroll</b></code> <code>(enroll)</code></summary>

##### Parameters

> | name | type     | data type | description |
> | ---- | -------- | --------- | ----------- |
> | id   | required | number    | N/A         |

##### Responses

```json
{
	"data": {
		"redirect": "https://test.thimpress.com/courses/les-acteurs-pornos-les-plus-riches-aujourdhui/lessons/introduction-2/"
	},
	"message": "Congrats! You have enrolled in the course successfully. Redirecting...",
	"status": "success"
}
```

</details>

---

<details>
 <summary><code>POST</code> <code><b>/wp-json/learnpress/v1/courses/finish</b></code> <code>(finishCourse)</code></summary>

##### Parameters

> | name | type     | data type | description |
> | ---- | -------- | --------- | ----------- |
> | id   | required | number    | N/A         |

##### Responses

```json
{
	"data": {},
	"message": "Congrats! You have completed the Course.",
	"status": "success"
}
```

</details>

---

<details>
 <summary><code>POST</code> <code><b>/wp-json/learnpress/v1/courses/retake</b></code> <code>(retakeCourse)</code></summary>

##### Parameters

> | name | type     | data type | description |
> | ---- | -------- | --------- | ----------- |
> | id   | required | number    | N/A         |

##### Responses

```json
{
	"data": {
		"url_redirect": "https://test.thimpress.com/courses/create-an-lms-website-with-learnpress/lessons/lms-website-and-learnpress-introduction/"
	},
	"message": "Now you can begin this course",
	"status": "success"
}
```

</details>

---

<details>
 <summary><code>POST</code> <code><b>/wp-json/learnpress/v1/lessons/finish</b></code> <code>(completeLesson)</code></summary>

##### Parameters

> | name | type     | data type | description |
> | ---- | -------- | --------- | ----------- |
> | id   | required | number    | N/A         |

##### Responses

```json
{
	"data": {},
	"message": "Congrats! You have completed the lesson successfully",
	"status": "success"
}
```

</details>

---

<details>
 <summary><code>GET</code> <code><b>/wp-json/learnpress/v1/quiz/${id}</b></code> <code>(quiz)</code></summary>

##### Parameters

##### Responses

```json
{"assigned": {"course": {"author": "3", "content": "The LearnPress myCRED Integration helps you improve your LMS website by adding a gamification system. So that you can give your students points, badges, and virtual currency as rewards, making the learning experience more engaging and motivating.

In this guide, let’s learn how to download, install, and configure the myCRED add-on for LearnPress.
What is the LearnPress myCred Integration?

LearnPress myCred integration, a useful add-on, is a seamless combination of two powerful plugins that bring gamification elements to your online courses. It helps you set up a points-based reward system in which students earn points for completing lessons, quizzes, assignments, and other course activities. Students can redeem these points for a variety of rewards or used to gain access to additional course content.

You can refer to our detailed video if it’s your first time creating an LMS website and looking for the best education WordPress themes.

Benefits of LearnPress myCred Integration

LearnPress myCred Integration offers several benefits for both online course creators and students. Some of the key advantages include:

    Increased Engagement: Gamification elements, such as points and rewards, motivate students to actively participate in the course and strive for better performance.
    Enhanced Learning Experience: Students gain a feeling of achievement by earning points and unlocking rewards, making the learning experience more enjoyable and fulfilling.
    Better Retention and Completion Rates: Gamification has been shown to improve student retention and course completion rates as it provides an additional incentive to stay engaged throughout the course.
    Encourages Healthy Competition: You can add leaderboards and badges to encourage healthy rivalries among learners while also promoting a sense of community.
    Flexible Reward System: Customize the points and rewards structure to align with your course objectives and create a unique learning environment.

Setting up the LearnPress myCred Integration
Download, Install, and Activate

First, you need to download the myCred add-on for LearnPress by visiting ThimPress and signing in to your account. Go to My Account -> Orders -> Download or Pick the version you want to get the add-on.", "id": "4559", "slug": "les-acteurs-pornos-les-plus-riches-aujourdhui", "title": "LearnPress myCred Integration: Step-by-Step Guide"}}, "can_finish_course": false, "content": "<p>Choose the correct answers</p>
", "date_created": "2022-06-13T04:18:54", "date_created_gmt": "2022-06-13T04:18:54", "date_modified": "2023-07-03T07:05:48", "date_modified_gmt": "2023-07-03T07:05:48", "duration": "1 minute", "excerpt": "", "id": 5531, "meta_data": {"_lp_duration": "1 minute", "_lp_instant_check": "yes", "_lp_minus_skip_questions": "no", "_lp_negative_marking": "no", "_lp_pagination": "1", "_lp_passing_grade": "80", "_lp_retake_count": "-1", "_lp_review": "yes", "_lp_show_correct_review": "yes"}, "name": "Quiz 1", "permalink": "https://test.thimpress.com/courses/les-acteurs-pornos-les-plus-riches-aujourdhui/quizzes/quiz-1-32/", "questions": [{"content": "<p>The multiple choice question type allows the respondent to choose one or multiple options from a list of possible answers. </p>
", "has_explanation": true, "hint": "1 & 2", "id": 5532, "object": [Object], "options": [Array], "point": 1, "title": "Multiple Choice", "type": "multi_choice"}, {"content": "<p>Single select questions are the questions where a respondent is asked to pick only one answer, from a predetermined set of responses of at least two or more options.</p>
", "has_explanation": true, "hint": "2", "id": 5533, "object": [Object], "options": [Array], "point": 1, "title": "Single Choice", "type": "single_choice"}, {"id": 5537, "object": [Object], "options": [Array], "point": 1, "title": "True or False question", "type": "true_or_false"}, {"content": "<p>A Fill in the Blank question consists of a phrase, sentence, or paragraph with a blank space where a student provides the missing word or words.</p>
", "id": 5538, "object": [Object], "options": [Array], "point": 1, "title": "Fill in blanks question", "type": "fill_in_blanks"}, {"content": "<p>Sorting questions are an engaging question type that can be used to get students to think critically about concepts in relation to one another.</p>
", "id": 5541, "object": [Object], "options": [Array], "point": 1, "title": "Sorting choice", "type": "sorting_choice"}], "results": {"duration": 60, "instant_check": true, "negative_marking": false, "page_numbers": false, "passing_grade": "80%", "questions_per_page": 0, "retake_count": -1, "review_questions": true, "status": "", "support_options": ["true_or_false", "single_choice", "multi_choice", "fill_in_blanks", "sorting_choice"]}, "slug": "quiz-1-32", "status": "publish"}
```

</details>

---

<details>
 <summary><code>POST</code> <code><b>/wp-json/learnpress/v1/quiz/start</b></code> <code>(quizStart)</code></summary>

##### Parameters

> | name | type     | data type | description |
> | ---- | -------- | --------- | ----------- |
> | id   | required | number    | N/A         |

##### Responses

```json
{"message": "", "results": {"attempts": [], "duration": 60, "question_ids": ["5532", "5533", "5537", "5538", "5541"], "questions": [[Object], [Object], [Object], [Object], [Object]], "retaken": 0, "status": "started", "total_time": 60, "user_item_id": 15263}, "status": "success"}
```

</details>

---

<details>
 <summary><code>POST</code> <code><b>/wp-json/learnpress/v1/quiz/finish</b></code> <code>(quizFinish)</code></summary>

##### Parameters

> | name     | type     | data type | description |
> | -------- | -------- | --------- | ----------- |
> | id       | required | number    | N/A         |
> | answered | required |           | N/A         |

##### Responses

```json
{"message": "", "results": {"answered": {"5532": [Object], "5533": [Object], "5537": [Object], "5538": [Object], "5541": [Object]}, "attempts": [[Object]], "mark": 5, "minus_point": 0, "pass": 0, "passing_grade": "80%", "question_answered": 1, "question_correct": 0, "question_count": 5, "question_empty": 4, "question_wrong": 1, "questions": {"5532": [Object], "5533": [Object], "5537": [Object], "5538": [Object], "5541": [Object]}, "result": 0, "results": {"answered": [Object], "attempts": [Array], "mark": 5, "minus_point": 0, "pass": 0, "passing_grade": "80%", "question_answered": 1, "question_correct": 0, "question_count": 5, "question_empty": 4, "question_wrong": 1, "questions": [Object], "result": 0, "status": "completed", "time_spend": "--:--", "user_mark": 0}, "status": "completed", "time_spend": "--:--", "user_mark": 0}, "status": "success"}
```

</details>

---

<details>
 <summary><code>GET</code> <code><b>/wp-json/learnpress/v1/users/${id}</b></code> <code>(getUser)</code></summary>

##### Parameters

##### Responses

```json
{"_links": {"collection": [[Object]], "self": [[Object]]}, "avatar_size": {"height": "250", "width": "250"}, "avatar_url": "", "custom_register": [], "description": "123", "email": "pcloc101099@gmail.com", "first_name": "123", "id": 2535, "instructor_data": {"active_courses": "3", "completed_courses": "2", "enrolled_courses": 5, "total_courses": 0, "total_users": 0}, "last_name": "123", "link": "https://test.thimpress.com/author/locpc/", "meta": [], "name": "locpc", "nickname": "locpc", "slug": "locpc", "social": {"facebook": "", "linkedin": "", "twitter": "", "youtube": ""}, "tabs": {"logout": {"content": "", "icon": "<i class=\"fas fa-sign-out-alt\"></i>", "priority": 100, "slug": "lp-logout", "title": "Logout"}, "my-courses": {"content": "", "icon": "<i class=\"fas fa-bars\"></i>", "priority": 1, "slug": "my-courses", "title": "My Courses"}, "order-details": {"content": "", "icon": false, "priority": 30, "slug": "order-details", "title": "Order details"}, "orders": {"content": [Object], "icon": "<i class=\"fas fa-shopping-cart\"></i>", "priority": 25, "slug": "orders", "title": "Orders"}, "quizzes": {"content": [Object], "icon": "<i class=\"fas fa-puzzle-piece\"></i>", "priority": 20, "slug": "quizzes", "title": "Quizzes"}, "settings": {"content": "", "icon": "<i class=\"fas fa-cog\"></i>", "priority": 90, "section": [Object], "slug": "settings", "title": "Settings"}}, "url": "", "username": "locpc"}
```

</details>

---

<details>
 <summary><code>POST</code> <code><b>/wp-json/learnpress/v1/users/${id}</b></code> <code>(updateUser)</code></summary>

##### Parameters

> | name           | type     | data type | description |
> | -------------- | -------- | --------- | ----------- |
> | first_name     | required | string    | N/A         |
> | last_name      | required | string    | N/A         |
> | nickname       | required | string    | N/A         |
> | description    | required | string    | N/A         |
> | lp_avatar_file | required | string    | N/A         |

##### Responses

```json
{"_links": {"collection": [[Object]], "self": [[Object]]}, "avatar_url": "", "capabilities": {"level_0": true, "read": true, "subscriber": true, "view_h5p_contents": true, "view_h5p_results": true, "view_others_h5p_contents": true}, "description": "1234", "email": "pcloc101099@gmail.com", "extra_capabilities": {"subscriber": true}, "first_name": "1234", "id": 2535, "last_name": "1234", "link": "https://test.thimpress.com/author/locpc/", "locale": "en_US", "meta": {"persisted_preferences": []}, "name": "locpc", "nickname": "locpc4", "registered_date": "2023-11-13T02:55:10+00:00", "roles": ["subscriber"], "slug": "locpc", "url": "", "username": "locpc"}
```

</details>

---

<details>
 <summary><code>GET</code> <code><b>/wp-json/wp/v2/course_category</b></code> <code>(getCategory)</code></summary>

##### Parameters

##### Responses

```json
[{"_links": {"about": [Array], "collection": [Array], "curies": [Array], "self": [Array], "wp:post_type": [Array]}, "count": 0, "description": "", "id": 4, "link": "https://test.thimpress.com/course-category/angular/", "meta": [], "name": "Angular", "parent": 0, "slug": "angular", "taxonomy": "course_category"}, {"_links": {"about": [Array], "collection": [Array], "curies": [Array], "self": [Array], "wp:post_type": [Array]}, "count": 3, "description": " ", "id": 10, "link": "https://test.thimpress.com/course-category/backend/", "meta": [], "name": "Backend", "parent": 0, "slug": "backend", "taxonomy": "course_category"}, {"_links": {"about": [Array], "collection": [Array], "curies": [Array], "self": [Array], "wp:post_type": [Array]}, "count": 2, "description": " ", "id": 8, "link": "https://test.thimpress.com/course-category/css/", "meta": [], "name": "CSS", "parent": 0, "slug": "css", "taxonomy": "course_category"}, {"_links": {"about": [Array], "collection": [Array], "curies": [Array], "self": [Array], "wp:post_type": [Array]}, "count": 1, "description": "  ", "id": 12, "link": "https://test.thimpress.com/course-category/frontend/", "meta": [], "name": "Frontend", "parent": 0, "slug": "frontend", "taxonomy": "course_category"}, {"_links": {"about": [Array], "collection": [Array], "curies": [Array], "self": [Array], "wp:post_type": [Array]}, "count": 2, "description": "   ", "id": 9, "link": "https://test.thimpress.com/course-category/general/", "meta": [], "name": "General", "parent": 0, "slug": "general", "taxonomy": "course_category"}, {"_links": {"about": [Array], "collection": [Array], "curies": [Array], "self": [Array], "wp:post_type": [Array]}, "count": 2, "description": " ", "id": 18, "link": "https://test.thimpress.com/course-category/it-software/", "meta": [], "name": "IT Software", "parent": 0, "slug": "it-software", "taxonomy": "course_category"}, {"_links": {"about": [Array], "collection": [Array], "curies": [Array], "self": [Array], "wp:post_type": [Array]}, "count": 2, "description": " ", "id": 21, "link": "https://test.thimpress.com/course-category/photography/", "meta": [], "name": "Photography", "parent": 0, "slug": "photography", "taxonomy": "course_category"}, {"_links": {"about": [Array], "collection": [Array], "curies": [Array], "self": [Array], "wp:post_type": [Array]}, "count": 3, "description": "  ", "id": 11, "link": "https://test.thimpress.com/course-category/programming-language/", "meta": [], "name": "Programming Language", "parent": 0, "slug": "programming-language", "taxonomy": "course_category"}, {"_links": {"about": [Array], "collection": [Array], "curies": [Array], "self": [Array], "wp:post_type": [Array]}, "count": 0, "description": "", "id": 2, "link": "https://test.thimpress.com/course-category/react/", "meta": [], "name": "React", "parent": 0, "slug": "react", "taxonomy": "course_category"}, {"_links": {"about": [Array], "collection": [Array], "curies": [Array], "self": [Array], "up": [Array], "wp:post_type": [Array]}, "count": 1, "description": "", "id": 30, "link": "https://test.thimpress.com/course-category/backend/sub-backend/", "meta": [], "name": "Sub Backend", "parent": 10, "slug": "sub-backend", "taxonomy": "course_category"}]
```

</details>

---

<details>
 <summary><code>POST</code> <code><b>/wp-json/learnpress/v1/wishlist/toggle</b></code> <code>(addRemoveWishlist)</code></summary>

##### Parameters

> | name | type     | data type | description |
> | ---- | -------- | --------- | ----------- |
> | id   | required | number    | N/A         |

##### Responses

```json
{"data": {"items": [[Object], [Object], [Object]], "text": {"add": "Add to wishlist", "remove": "Remove from wishlist"}, "type": "add"}, "message": "This course has been added to your wishlists", "status": "success"}
```

</details>

---

<details>
 <summary><code>GET</code> <code><b>/wp-json/learnpress/v1/wishlist</b></code> <code>(getWishlist)</code></summary>

##### Parameters

> | name     | type     | data type | description |
> | -------- | -------- | --------- | ----------- |
> | page     | required |           | N/A         |
> | per_page | required |           | N/A         |
> | optimize | required | true      | N/A         |

##### Responses

```json
{"data": {"items": [[Object], [Object], [Object]]}, "message": "", "status": "success"}
```

</details>

---

<details>
 <summary><code>GET</code> <code><b>/wp-json/learnpress/v1/wishlist/course/${id}</b></code> <code>(getWishlistWithId)</code></summary>

##### Parameters

##### Responses

```json
{"data": {"in_wishlist": "yes", "items": [[Object], [Object], [Object]], "text": {"add": "Add to wishlist", "remove": "Remove from wishlist"}}, "message": "This course available in your wishlist", "status": "success"}
```

</details>

---

<details>
 <summary><code>GET</code> <code><b>/wp-json/learnpress/v1/assignments/${id}</b></code> <code>(getAssignment)</code></summary>

##### Parameters

##### Responses

```json
{"allow_file_type": "jpg,txt,zip,pdf,doc,docx,ppt", "assigned": {"course": {"author": "1", "content": "<h4>COURSE DESCRIPTION</h4>
<span class=\"style-scope yt-formatted-string\" dir=\"auto\">A series of Videos from ThimPress, give you a detailed tutorial to create an LMS Website with LearnPress - LMS &amp; Education WordPress Plugin.</span>

https://www.youtube.com/watch?v=5jdAYTjj3LM

This course is a detailed and easy tutorial to get you all setup and going with the use of <a href=\"https://wordpress.org/plugins/learnpress/\" target=\"_blank\" rel=\"noopener\"><strong>LearnPress LMS Plugin</strong></a>. It is a free and simple plugin to help you create an <strong>Online Courses Website</strong> step by step. The tutorial guides you through the configuration of the plugin, creation of Courses, Lessons, Quizzes, and finally guides you on how to boost up your Website with <a href=\"https://thimpress.com/wordpress/plugins/learnpress/?utm_source=Eduma&amp;utm_medium=Course&amp;utm_campaign=LMSWebsite\" target=\"_blank\" rel=\"noopener\"><strong>Premium LearnPress Add-ons</strong></a> brought to you by ThimPress (creator of LearnPress). It also shows how you could configure additional items like the course layouts and featured images.
<h4>CERTIFICATION</h4>
Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry’s standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.
<h4>LEARNING OUTCOMES</h4>
<ul class=\"thim-list-content\">
        <li>Over 37 lectures and 55.5 hours of content!</li>
        <li>Testing Training Included.</li>
        <li>Learn Software Testing and Automation basics from a professional trainer from your own desk.</li>
        <li>Information packed practical training starting from basics to advanced testing techniques.</li>
        <li>Best suitable for beginners to advanced level users and who learn faster when demonstrated.</li>
        <li>Course content designed by considering current software testing technology and the job market.</li>
        <li>Practical assignments at the end of every session.</li>
        <li>Practical learning experience with live project work and examples.</li>
</ul>", "id": "7178", "slug": "introduction-learnpress-lms-plugin", "title": "Introduction LearnPress - LMS plugin"}}, "assignment_answer": {"file": [], "note": "123123"}, "attachment": [{"id": "7887", "name": "f.html", "url": "https://test.thimpress.com/wp-content/uploads/2023/02/f.html"}], "can_finish_course": false, "content": "<p>213</p>
", "date_created": "2021-12-26T12:03:37", "date_created_gmt": "2021-12-26T12:03:37", "date_modified": "2023-10-23T10:12:30", "date_modified_gmt": "2023-10-23T03:12:30", "duration": {"format": "10 hours", "time": 36000, "time_remaining": 28094}, "evaluation": [], "excerpt": "", "files_amount": 1, "id": 963, "introdution": "123123", "name": "Assignment", "passing_grade": "6.4", "permalink": "https://test.thimpress.com/courses/introduction-learnpress-lms-plugin/assignments/assignment-3/", "results": {"end_time": false, "expiration_time": "2023-11-14T16:31:22", "start_time": "2023-11-14T06:31:22", "status": "doing"}, "retake_count": 100, "retaken": 3, "slug": "assignment-3", "status": "publish"}
```

</details>

---

<details>
 <summary><code>POST</code> <code><b>/wp-json/learnpress/v1/assignments/start/</b></code> <code>(startAssignment)</code></summary>

##### Parameters

> | name | type     | data type | description |
> | ---- | -------- | --------- | ----------- |
> | id   | required | number    | N/A         |

##### Responses

```json
{
	"data": { "status": 200 },
	"message": "Your Assignment has been started successfully."
}
```

</details>

---

<details>
 <summary><code>POST</code> <code><b>/wp-json/learnpress/v1/assignments/retake/</b></code> <code>(retakeAssignment)</code></summary>

##### Parameters

> | name | type     | data type | description |
> | ---- | -------- | --------- | ----------- |
> | id   | required |           | N/A         |

##### Responses

```json
{
	"data": { "status": 200 },
	"message": "Your Assignment has been started successfully."
}
```

</details>

---

<details>
 <summary><code>POST</code> <code><b>/wp-json/learnpress/v1/assignments/submit/</b></code> <code>(saveSendAssignment)</code></summary>

##### Parameters

> | name   | type     | data type | description |
> | ------ | -------- | --------- | ----------- |
> | action | required |           | N/A         |
> | id     | required |           | N/A         |
> | note   | required |           | N/A         |
> | file[] | required |           | N/A         |

##### Responses

```json
{
	"data": { "status": 200 },
	"message": "The progress was saved! Your file(s) were uploaded successfully!"
}
```

</details>

---

<details>
 <summary><code>POST</code> <code><b>/wp-json/learnpress/v1/assignments/delete-submit-file/</b></code> <code>(deleteFileAssignment)</code></summary>

##### Parameters

> | name   | type     | data type | description |
> | ------ | -------- | --------- | ----------- |
> | fileId | required |           | N/A         |
> | id     | required |           | N/A         |

##### Responses

```json
response {"data": {"status": 200}, "message": "Remove file successfully"}
```

</details>

---

<details>
 <summary><code>GET</code> <code><b>/wp-json/learnpress/v1/courses</b></code> <code>(topCoursesWithStudent)</code></summary>

##### Parameters

> | name | type     | data type             | description |
> | ---- | -------- | --------------------- | ----------- |
> | None | required | object (JSON or YAML) | N/A         |

##### Responses

```json

```

</details>

---

<details>
 <summary><code>GET</code> <code><b>/wp-json/learnpress/v1/courses</b></code> <code>(newCourses)</code></summary>

##### Parameters

> | name | type     | data type             | description |
> | ---- | -------- | --------------------- | ----------- |
> | None | required | object (JSON or YAML) | N/A         |

##### Responses

```json

```

</details>

---

<details>
 <summary><code>GET</code> <code><b>/wp-json/learnpress/v1/users</b></code> <code>(getIntructor)</code></summary>

##### Parameters

> | name  | type     | data type                       | description |
> | ----- | -------- | ------------------------------- | ----------- |
> | roles | required | ['lp_teacher', 'administrator'] | N/A         |

##### Responses

```json
[{"_links": {"collection": [Array], "self": [Array]}, "avatar_size": {"height": "250", "width": "250"}, "avatar_url": "https://test.thimpress.com/wp-content/uploads/learn-press-profile/3/42f94c6a5e6bee2bc6033f338414c017.jpg", "custom_register": [], "description": "", "email": "gittaamelia83@gmail.com", "first_name": "Instructor", "id": 3, "instructor_data": {"active_courses": 0, "completed_courses": 0, "enrolled_courses": 0, "total_courses": 3, "total_users": 24}, "last_name": "One", "link": "https://test.thimpress.com/author/instructor/", "meta": [], "name": "Instructor One", "nickname": "instructor", "slug": "instructor", "social": {"facebook": "", "linkedin": "", "twitter": "", "youtube": ""}, "tabs": [], "url": "", "username": "instructor"}, {"_links": {"collection": [Array], "self": [Array]}, "avatar_size": {"height": "250", "width": "250"}, "avatar_url": "https://test.thimpress.com/wp-content/uploads/learn-press-profile/5/e355acc3635694763cb5bb1b7ed78e5d.jpg", "custom_register": [], "description": "giáo viên Tin học", "email": "in2@g.com", "first_name": "Instructor", "id": 5, "instructor_data": {"active_courses": 0, "completed_courses": 0, "enrolled_courses": 0, "total_courses": 1, "total_users": 5}, "last_name": "Three", "link": "https://test.thimpress.com/author/instructor2/", "meta": [], "name": "Instructor Three", "nickname": "instructor2", "slug": "instructor2", "social": {"facebook": "", "linkedin": "", "twitter": "", "youtube": ""}, "tabs": [], "url": "http://pensive-tesla", "username": "instructor2"}, {"_links": {"collection": [Array], "self": [Array]}, "avatar_size": {"height": "250", "width": "250"}, "avatar_url": "https://test.thimpress.com/wp-content/uploads/learn-press-profile/4/2bdc11605b0206b672a2f16ab575be81.jpg", "custom_register": [], "description": "giáo viên Toán", "email": "in1@g.com", "first_name": "Instructor", "id": 4, "instructor_data": {"active_courses": 0, "completed_courses": 0, "enrolled_courses": 0, "total_courses": 3, "total_users": 20}, "last_name": "Two", "link": "https://test.thimpress.com/author/instructor1/", "meta": [], "name": "Instructor Two", "nickname": "instructor1", "slug": "instructor1", "social": {"facebook": "https://docs.google.com/spreadsheets/d/1oFiD47UfrbikPfhC1xpvAALzTxVPoAY1BmVlF6MuyE8/edit#gid=792097700", "linkedin": "https://docs.google.com/spreadsheets/d/1oFiD47UfrbikPfhC1xpvAALzTxVPoAY1BmVlF6MuyE8/edit#gid=792097700", "twitter": "https://docs.google.com/spreadsheets/d/1oFiD47UfrbikPfhC1xpvAALzTxVPoAY1BmVlF6MuyE8/edit#gid=792097700", "youtube": "https://docs.google.com/spreadsheets/d/1oFiD47UfrbikPfhC1xpvAALzTxVPoAY1BmVlF6MuyE8/edit#gid=792097700"}, "tabs": [], "url": "http://pensive-tesla", "username": "instructor1"}, {"_links": {"collection": [Array], "self": [Array]}, "avatar_size": {"height": "250", "width": "250"}, "avatar_url": "", "custom_register": [], "description": "", "email": "intest@g.com", "first_name": "Intest", "id": 2092, "instructor_data": {"active_courses": 0, "completed_courses": 0, "enrolled_courses": 0, "total_courses": 0, "total_users": 0}, "last_name": "123", "link": "https://test.thimpress.com/author/intest/", "meta": [], "name": "Intest 123", "nickname": "intest", "slug": "intest", "social": {"facebook": "", "linkedin": "", "twitter": "", "youtube": ""}, "tabs": [], "url": "http://sdfsdfsdf", "username": "intest"}, {"_links": {"collection": [Array], "self": [Array]}, "avatar_size": {"height": "250", "width": "250"}, "avatar_url": "", "custom_register": [], "description": "For React Native, we decided to use web paradigm for this where you can nest text to achieve the same effect.", "email": "admin@test.thimpress.com", "first_name": "", "id": 1, "instructor_data": {"active_courses": "1", "completed_courses": "0", "enrolled_courses": 1, "total_courses": 13, "total_users": 128}, "last_name": "", "link": "https://test.thimpress.com/author/pensive-tesla/", "meta": [], "name": "pensive-tesla", "nickname": "pensive-tesla", "slug": "pensive-tesla", "social": {"facebook": "https://mail.google.com/mail/u/2/#inbox", "linkedin": "https://mail.google.com/mail/u/2/#inbox", "twitter": "https://mail.google.com/mail/u/2/#inbox", "youtube": "https://mail.google.com/mail/u/2/#inbox"}, "tabs": [], "url": "https://test.thimpress.com", "username": "pensive-tesla"}, {"_links": {"collection": [Array], "self": [Array]}, "avatar_size": {"height": "250", "width": "250"}, "avatar_url": "", "custom_register": [], "description": "", "email": "thanhthanhikon@gmail.com", "first_name": "Thanh", "id": 2428, "instructor_data": {"active_courses": 0, "completed_courses": 0, "enrolled_courses": 0, "total_courses": 0, "total_users": 0}, "last_name": "Pham", "link": "https://test.thimpress.com/author/thanh-pham-ad/", "meta": [], "name": "Thanh Pham", "nickname": "Thanh Pham ad", "slug": "thanh-pham-ad", "social": {"facebook": "", "linkedin": "", "twitter": "", "youtube": ""}, "tabs": [], "url": "", "username": "Thanh Pham ad"}]
```

</details>

---

<details>
 <summary><code>GET</code> <code><b>/wp-json/learnpress/v1/course_category</b></code> <code>(getCategoryHome)</code></summary>

##### Parameters

##### Responses

```json

```

</details>

---

<details>
 <summary><code>GET</code> <code><b>/wp-json/learnpress/v1/review/course/${id}</b></code> <code>(getReview)</code></summary>

##### Parameters

##### Responses

```json
{"data": {"can_review": false, "comment_approved": 0, "items": {"1": {"percent": 0, "percent_float": 0, "rated": 1, "total": 0}, "2": {"percent": 6, "percent_float": 0, "rated": 2, "total": 1}, "3": {"percent": 12, "percent_float": 0, "rated": 3, "total": 2}, "4": {"percent": 0, "percent_float": 0, "rated": 4, "total": 0}, "5": {"percent": 81, "percent_float": 0, "rated": 5, "total": 13}}, "rated": 4.5625, "reviews": {"paged": 1, "pages": 6, "per_page": 3, "reviews": [Array], "total": 16}, "total": 16}, "message": "You have already reviewed this course. It will be visible after it has been approved", "status": "success"}
```

</details>

---

<details>
 <summary><code>POST</code> <code><b>/wp-json/learnpress/v1/review/submit</b></code> <code>(createReview)</code></summary>

##### Parameters

> | name    | type     | data type | description |
> | ------- | -------- | --------- | ----------- |
> | id      | required |           | N/A         |
> | title   | required |           | N/A         |
> | rate    | required |           | N/A         |
> | content | required |           | N/A         |

##### Responses

```json
{
	"data": { "comment_id": 258 },
	"message": "Thank you for your review. Your review will be visible after it has been approved",
	"status": "success"
}
```

</details>

---

<details>
 <summary><code>POST</code> <code><b>/wp-json/learnpress/v1/quiz/check_answer</b></code> <code>(checkAnswer)</code></summary>

##### Parameters

> | name        | type     | data type | description |
> | ----------- | -------- | --------- | ----------- |
> | id          | required |           | N/A         |
> | question_id | required |           | N/A         |
> | answered    | required |           | N/A         |

##### Responses

```json
{
	"explanation": "Hello",
	"message": "",
	"options": [
		{ "is_true": "yes", "title": "True", "uid": 5029, "value": "true" },
		{ "is_true": "", "title": "False", "uid": 5030, "value": "false" }
	],
	"result": { "answered": "true", "correct": true, "mark": 1 },
	"status": "success"
}
```

</details>

---

<details>
 <summary><code>POST</code> <code><b>/wp-json/learnpress/v1/users/reset-password</b></code> <code>(resetEmail)</code></summary>

##### Parameters

> | name | type     | data type             | description |
> | ---- | -------- | --------------------- | ----------- |
> | None | required | object (JSON or YAML) | N/A         |

##### Responses

```json

```

</details>

---

<details>
 <summary><code>POST</code> <code><b>/wp-json/learnpress/v1/users/change-password</b></code> <code>(changePassword)</code></summary>

##### Parameters

> | name | type     | data type             | description |
> | ---- | -------- | --------------------- | ----------- |
> | None | required | object (JSON or YAML) | N/A         |

##### Responses

```json

```

## </details>

<details>
 <summary><code>POST</code> <code><b>/wp-json/learnpress/v1/users/delete</b></code> <code>(deleteAccount)</code></summary>

##### Parameters

> | name | type     | data type             | description |
> | ---- | -------- | --------------------- | ----------- |
> | None | required | object (JSON or YAML) | N/A         |

##### Responses

```json

```

</details>

---

<details>
 <summary><code>POST</code> <code><b>/wp-json/learnpress/v1/push-notifications/register-device</b></code> <code>(registerFCMToken)</code></summary>

##### Parameters

> | name         | type     | data type | description |
> | ------------ | -------- | --------- | ----------- |
> | device_token | required |           | N/A         |
> | device_type  | required |           | N/A         |

##### Responses

```json

```

</details>

---

<details>
 <summary><code>POST</code> <code><b>/wp-json/learnpress/v1/push-notifications/delete-device</b></code> <code>(deleteFCMToken)</code></summary>

##### Parameters

> | name         | type     | data type | description |
> | ------------ | -------- | --------- | ----------- |
> | device_token | required |           | N/A         |

##### Responses

```json

```

</details>

---

<details>
 <summary><code>GET</code> <code><b>/wp-json/learnpress/v1/push-notifications/get-notifications</b></code> <code>(getNotifications)</code></summary>

##### Parameters

##### Responses

```json
{
	"data": [
		{
			"content": "React Native LMS Mobile App for iOS & Android.",
			"id": 1,
			"time": "10:00 23/12/2022",
			"title": "Welcome to Eduma App"
		},
		{
			"content": "Education WordPress Theme – Eduma is made for Education Website, LMS, Training Center, Courses Hub, College, Academy, University, School, Kindergarten, etc.",
			"id": 2,
			"time": "10:00 23/12/2022",
			"title": ""
		},
		{
			"content": "Push Notification will be added soon. We are working on it. Thank you for your patience.",
			"id": 3,
			"time": "15:00 23/12/2022",
			"title": ""
		}
	],
	"success": true,
	"total_pages": 1
}
```

</details>
