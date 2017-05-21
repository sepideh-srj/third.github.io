# By Sepide Sarajian
&#x202b;
<p dir="rtl">برای صفحه های مختلف به استایل های مختلفی نیاز داریم که باعث می شوند صفحه های وبی که می سازیم زیباتر شوند و استفاده از آن ها راحت تر باشد. برای این کار ما صفحات را ریسپانسیو می کنیم که یکی از قسمت های آن تصویر های ریسپانسیو است. برای ریسپانسیو کردن تصویر ها باید به ابعاد دستگاه، ابعاد تصویر و رزولوشن صفحه ی دستگاه توجه نمود.

اگر سایز اصلی عکس را برای متناسب کردن آن با صفحه عوض کنیم تصویر اصلی عوض شده و راه حل مناسبی نمی تواند باشد همچنین اگر سایز تصویر را همیشه بزرگترین حالت ممکن در نظر بگیریم در حالت های کوچک تر تصویرهای بزرگی استفاده شده اند که کاربردی ندارند و سرعت را کاهش می دهند پس این نیز راه حل مناسبی نیست. با توجه به فرمت عکس دو روش وجود دارد:

یک) اگر تصویر SVG باشد چون این تصاویر بر اساس بردار هستند در سایز های مختلف مشکلی ایجاد نمی کنند و با استفاده از صفت های width  و max width با توجه به صفحه تغییر می کنند و به تصویر های متفاوت نیاز نداریم.

دو) اگر تصویر PNG یا GIF یا JGP باشد که برخلاف حالت قبل براساس پیکسل هستند برای رزولوشن ها و ابعاد مختلف صفحه به تصویرهای متفاوت نیاز داریم در دستگاه هایی که صفحه ی رترینا دارند با اضافه کردن صفت srcset می توانیم تصویر های جایگزین برای داشته باشیم. برای ابعاد مختلف از width تصویر استفاده می کنیم و برای مشخص کردن ابعاد تصویر در صفحه از صفت سایز استفاده می کنیم.

گاهی اوقات کارهایی که در بالا انجام دادیم باعث زیبایی بیشتر صفحه نشده اند و در صفحه های مختلف با تصاویری که نسبت ابعادشان متفاوت است به نتایج بهتری میرسیم در این مواقع از تگ picture و source استفاده می کنیم و با استفاده از صفت های media و srcset تصاویری که در هر صفحه  بهتر اند را انتخاب می کنند که می توانند کاملا با یکدیگر متفاوت باشند.
</p>
