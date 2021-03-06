---
toc: true
layout: post
description: تعلم فيما يستهدم Amazon Kinesis.
categories: [markdown]
title: Amazon Kinesis بالعربي احلا part 1
comments: true
image: images/Amazon-Kinesis.png
---

 
# Amazon Kinesis 
هي عائلة من الخدمات التي تقدمها امازون والتي تسمح لنا بجمع وتحليل البيانات المتدفقة في ذات الوقت حيث يمكنك الحصول علي رؤية كامله عن البيانات في الوقت الفعلي و اتخاذ اجراء في الوقت المناسب 
يمكن ان تكون تلك البيانات هي عبارة عن ضغطات على الشاشة في موقع معين او حساسات مستخدمة في مشروع انترنت الاشياء او حتى اصوات وصور من كاميرات المراقبة 

تحتوي عائلة كينيسيس على أكثر من فرد سوف نتعرف عليهم لاحقا في هذه السلسلة من المقالات 

فوائد خدمات عائلة Amazon Kinesis:

1. 	يمكنها من استيعاب البيانات المتدفقة في نفس لحظة توليدها وتحليلها او تخزينها لمعالجتها في وقت لاحق او اتخاذ قرار في نفس الوقت
2.	هي خدمة مدارة بالكامل ولا تحتاج اي بنية تحتية ويمكن ربطها مباشرة بالتطبيق الخاص بها 
3. 	خدمة قابلة للتوسع حيث يمكنها التعامل مع اي كمية بيانات مهما كانت حجمها ويمكن ربطها بمئات الالاف من المصادر 

بعض تطبيقات عائلة كينيسيس :

1.	تحليل فيديوهات كاميرات المراقبة والتعرف على الوجوه:
يمكن استخدام كينيسيس لتحويل تدفق البيانات من كاميرات المراقبة مباشرة الي امازون بعد ذالك تتم معالجة الفيديوهات والتعرف على الوجوه والعلامات التجارية وغيرها في غضون ثوان 
مثال: نظام تنبيه Amber

 
![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/e9licoxv0qli32nk7otb.png)
 

2.	الانتقال من مرحلة تحليل البيانات المجمعة الي التحليل في نفس وقت جمع البيانات 
يمكنك تحليل البيانات في نفس وقت التقاطها عوضا عن استخدام الاساليب التقليدية من جمع البيانات اولا ومن ثم تحليلها وايضا يمكنك تخزين البيانات التي تم تحليلها لاستخدامها لأغراض اخري

مثال علي ذالك، شركة Zillow،
 تقوم الشركة بتحديث تقديرات اسعار المنازل بشكل سريع ليتسنى لمشترين المنازل والبائعين الاطلاع علي أحدث تقديرات اسعار المنازل 

3.	تطوير التطبيقات في الوقت الفعلي
يمكن استخدام كينيسيس  لمراقبة التطبيقات في الوقت اللحظي لاكتشاف الاحتيال او الاضرار وحلها سريعا كما تفعل شركة Netflix
 حيث تستخدم كينيسيس لمراقبة الاتصالات بين جميع تطبيقاتها بحيث يمكنها اكتشاف المشكلات وحلها بسرعة، مما يضمن ارتفاع وقت تشغيل الخدمة وتوفرها لعملائها

4.	تحليل بيانات أجهزة إنترنت الأشياء 
يمكن استخدام كينيسيس لمعالجة البيانات المتدفقة من الحساسات مثل اجهزة الاستشعار والاستقبال وغيرها، يمكن استخدام كينيسيس لإرسال تنبيه او اتخاذ اجراء ويمكن ايضا دمجها بنموذج تعلم الي مثل تطبيق استشعار الاجهزة الموجودة في الجرار الي إحدى قطع الغيار فتقوم بإرسال الطلب تلقائيًا
 
![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/qmdhyb1b6mgo0ihkqcya.png)


كانت هذه مقدمة سريعة لخدمات عائلة كينيسيس  فيما يلي سنتعرف علي افراد العائلة كلا علي حدا لذالك تابع سلسلة المقالات هذه 
شكرا علي وقت القراءة ```اراك في المقال التالي ```


