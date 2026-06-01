# lisan345

## Description / وصف
هذه قائمة كاملة بالجذور الثلاثية والرباعية والخماسية في لسان العرب، موسومة بالعربية وبالنقل الحرفي، مع تحليل كل صامت بحسب مخرجه وصفته. تستند هذه البيانات إلى الطبعة الرقمية المتاحة على موقع الورّاق: https://alwaraq.net/book-view/89.
ويتبع وصف الصوامت العربية من حيث المخارج والصفات 

Janet C.E. Watson, _The Phonology and Morphology of Arabic_ (Oxford: Oxford University Press), p. 13.

يمكن استخدام lisan345 بوصفه قاعدة بيانات منظّمة لدراسة البنية الصوتية للجذور العربية في لسان العرب. فهو يتيح فحص الجذور الثلاثية والرباعية والخماسية بحسب حروفها، ومخارج هذه الحروف وصفاتها النطقية. وبذلك يمكن للباحث تتبّع الأنماط الصوتية داخل الجذر، مثل تجاور الصوامت المتقاربة في المخرج أو الصفة، أو غياب بعض التراكيب الصوتية. كما يمكن استعماله لاختبار قضايا مثل التنافر الصوتي أو شبه التنافر بين الحروف المتشابهة، وهي قضايا يناقشها أورهان الماس في دراسته للبنية الصوتية للجذور العربية (Elmaz 2011, 75–78). ويفيد أيضًا في الدراسات المعجمية، والحوسبة اللغوية، وتحليل القيود الصوتية على تكوين الجذر.

This is a complete list of the triliteral, quadriliteral, and quinquiliteral roots in the _Lisān al-ʿArab_, labelled in Arabic and transliteration, with each consonant analysed according to its place and manner of articulation. This data is based on the digitised edition available at https://alwaraq.net/book-view/89. The phonetic description of Arabic consonants in terms of place and manner of articulation follows Janet C.E. Watson, _The Phonology and Morphology of Arabic_ (Oxford: Oxford University Press), p. 13.

lisan345 can be used as a structured dataset for studying the phonetic structure of Arabic roots in Lisān al-ʿArab. It makes it possible to examine triliteral, quadriliteral, and quinquiliteral roots according to their consonants, places of articulation, and manners of articulation. Researchers can use it to identify patterns in root structure, such as clusters of consonants that are similar in place or manner, or combinations that are rare or absent. It is especially useful for investigating phonetic incompatibility or near-incompatibility among similar consonants, a topic discussed by Elmaz in relation to the phonetic structure of Arabic roots (Elmaz 2011, 75–78). The dataset can also support comparative work on Arabic and Semitic root structure, lexical studies, computational linguistics, and quantitative analyses of phonological constraints.

## Statistics / الإحصائيات
عدد الجذور الثلاثية: 6529

عدد الجذور الرباعية: 2551

عدد الجذور الخماسية: 183

Triliteral (ثلاثي) roots: 6529

Quadriliteral (رباعي) roots: 2551

Quinquiliteral  (خماسي) roots: 183

## File structure / بنية الملفات
يحتوي مجلد data على ملف CSV لكل مجموعة من الجذور المستخرجة من لسان العرب.

* The folder "data" contains a csv file for each set of roots from the _Lisān al-ʿArab_

## Data Structure / بنية البيانات
حتوي كل ملف CSV على رؤوس أعمدة لكل مجموعة من الجذور، ويورد الجذر بالعربية (LAB_ar) وبالنقل الحرفي (LAB_tr). ويُحلَّل كل حرف من حروف الجذر بحسب ترتيبه في الأبجدية العربية (C) ومخرجه (P) وصفته/طريقة نطقه (M).

A csv file with headers for each set of roots, listing the root in Arabic (LAB_ar) and in transliteration (LAB_tr). Each literal is further analysed by its order in the Arabic alphabet (C) and its place (P) and manner (M) of articulation.

	LAB_ar	LAB_tr	LAB1	LAB2	LAB3	LAB4	LAB5	C1	C2	C3	C4	C5	P1	P2	P3	P4	P5	M1	M2	M3	M4	M5
	عندلب	ʿNDLB	ʿ	N	D	L	B	18	25	8	23	2	8	4	4	4	1	3	5	1	6	1

الصوامت بحسب مخارجها هي كما يلي:

1:= شفوي = {ب، م}، 
2:= شفوي أسناني = {ف}، 
3:= بين أسناني = {ث، ذ، ظ}، 
4:= أسناني لثوي = {ت، د، ط، س، ز، ص، ن، ل، ض، ر}، 
5:= غاري = {ج، ش، ي}، 
6:= طبقي = {ك، و}، 
7:= لهوي = {ق، خ، غ}، 
8:= حلقي = {ح، ع}، 
9:= حنجري = {أ، ه}

الصوامت بحسب صفاتها النطقية هي كما يلي:

1:= انفجاري = {ب، ت، د، ج، ك، ق، أ}، 
2:= انفجاري مفخّم = {ط}، 
3:= احتكاكي = {ف، ث، ذ، س، ز، ش، خ، غ، ح، ع، ه}، 
4:= احتكاكي مفخّم = {ظ، ص}، 
5:= أنفي = {م، ن}، 
6:= جانبي = {ل}، 
7:= جانبي مفخّم = {ض}، 
8:= نقري = {ر}، 
9:= منزلق = {ي، و}


The consonants by place of articulation are as follows:
1:= Labial = {B, M}, 
2:= Labiodental = {F}, 
3:= Interdental = {Ṯ, Ḏ. Ẓ}, 
4:= Dentalalveolar	= {T, D, Ṭ, Ṣ, Z, Ṣ, N, L, Ḍ, R}, 
5:= Palatal	= {Ǧ, Š, Y}, 
6:= Velar = {K, W}, 
7:= Uvular	= {Q, Ḫ, Ġ}, 
8:= Pharyngeal = {Ḥ, ʿ}, 
9:= Laryngeal = {ʾ, H}

The consonants by manner of articulation are as follows:
1:= Plosive = {B, T, D, Ǧ, K, Q, ʾ}, 
2:= emphatic Plosive = {Ṭ}, 
3:= Fricative = {F, Ṯ, Ḏ, S, Z, Š, Ḫ, Ġ, Ḥ, ʿ, H}, 
4:= emphatic Fricative = {Ẓ, Ṣ}, 
5:= Nasal = {M, N}, 
6:= Lateral = {L}, 
7:= emphatic Lateral = {Ḍ}, 
8:= Tap = {R}, 
9:= Glide = {Y, W}

## Citation / الاستشهاد
يمكن الاستشهاد بهذه البيانات على النحو الآتي:

You can cite this data as

	Elmaz, Orhan. 2026. Lisan345. http://github.com/git85hub/lisan345.

أو بوصفها جزءًا من الكتاب المنشور:

or as part of the published book:

  	Elmaz, Orhan. Studien zu den koranischen Hapaxlegomena unikaler Wurzeln (Wiesbaden: Harrassowitz, 2011), 303-317.

