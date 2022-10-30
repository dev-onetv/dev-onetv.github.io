<script>
function shareFunction() {
  if (navigator.share) {
    navigator.share({
        title: 'این برنامه را مشاهده کنید: "OneTV - ماهواره و تلویزیون"',
        text: 'شبکه های تلویزیونی فارسی، کردی (و بسیاری از زبان های دیگر) را به صورت زنده در برنامه "OneTV - ماهواره و تلویزیون" تماشا کنید. می توانید برنامه را از آدرس زیر دانلود کنید:',
        url: 'https://dev-onetv.github.io/download/index_fa',
      })
      .catch((error) => console.log('Error sharing', error));
  } else {
    var email = 'sample@gmail.com';
    var subject = 'Checkout "OneTV - Persian TV"';
    var emailBody = 'شبکه های تلویزیونی فارسی، کردی (و بسیاری از زبان های دیگر) را به صورت زنده در "OneTV - ماهواره و تلویزیون" تماشا کنید. می توانید برنامه را از آدرس زیر دانلود کنید: https://dev-onetv.github.io/download/index_fa';
    var isWebView = navigator.userAgent.indexOf("Android") != -1;
    if (! isWebView) {
<!--       document.location = "mailto:?subject="+subject+"&body="+emailBody; -->
    }
  }
}
</script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>

<div dir="rtl" alight="right">

### **دانلود وان تی وی (آخرین نسخه: ۳۰.۰، ۲۵ شهریور ۱۴۰۱)**

*   [گوگل پلی](https://play.google.com/store/apps/details?id=com.kamal.androidtv){:target="_blank"}

*   [دانلود مستقیم](https://github.com/dev-onetv/dev-onetv.github.io/raw/main/releases/OneTV_Release_30_0.apk){:target="_blank"}

*   [آمازون اپ استور](https://www.amazon.com/developer-onetv-gmail-com-OneTV-Persian-TV/dp/B09T2L7GN1){:target="_blank"}

*   [ای پی کی کمبو](https://apkcombo.com/onetv-persian-tv/com.kamal.androidtv/){:target="_blank"}

*   [مایکت](https://myket.ir/app/com.kamal.androidtv){:target="_blank"}


</div>


<p align="center">
  <button id='share-button' onclick="shareFunction()" style="background-color: #111827; border: 1px solid transparent; border-radius: .75rem; box-sizing: border-box; color: #FFFFFF; cursor: pointer; flex: 0 0 auto; font-family: 'Inter var',ui-sans-serif,system-ui,-apple-system,system-ui,'Segoe UI',Roboto,'Helvetica Neue',Arial,'Noto Sans',sans-serif,'Apple Color Emoji','Segoe UI Emoji','Segoe UI Symbol','Noto Color Emoji'; font-size: 1.125rem; font-weight: 600; line-height: 1.5rem; padding: .75rem 1.2rem; text-align: center; text-decoration: none #6B7280 solid; text-decoration-thickness: auto; transition-duration: .2s; transition-property: background-color,border-color,color,fill,stroke; transition-timing-function: cubic-bezier(.4, 0, 0.2, 1); user-select: none; -webkit-user-select: none; touch-action: manipulation; width: auto;">به اشتراک گذاشتن</button>
  
  <br/><br/>
  
  <img src="https://github.com/dev-onetv/dev-onetv.github.io/raw/main/images/webpage_qr_code.png" alt="کد کیو آر برای اسکن" style="width:200px;" onclick="shareFunction()"/>
</p>

