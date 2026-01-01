<script>
function shareFunction() {
  if (navigator.share) {
    navigator.share({
        title: 'Checkout "OneElevate TV - Persian TV"',
        text: 'Checkout "OneElevate TV - Persian TV" at: ',
        url: 'https://dev-onetv.github.io/',
      })
      .catch((error) => console.log('Error sharing', error));
  } else {
    var email = 'sample@gmail.com';
    var subject = 'Checkout "OneElevate TV - Persian TV"';
    var emailBody = 'Checkout "OneElevate TV - Persian TV" at: https://dev-onetv.github.io/';
    document.location = "mailto:?subject="+subject+"&body="+emailBody;
  }
}
</script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>

### **Share OneElevate TV - به اشتراک گذاشتن**
   <button id='share-button' onclick="shareFunction()" style="background-color: #111827; border: 1px solid transparent; border-radius: .75rem; box-sizing: border-box; color: #FFFFFF; cursor: pointer; flex: 0 0 auto; font-family: 'Inter var',ui-sans-serif,system-ui,-apple-system,system-ui,'Segoe UI',Roboto,'Helvetica Neue',Arial,'Noto Sans',sans-serif,'Apple Color Emoji','Segoe UI Emoji','Segoe UI Symbol','Noto Color Emoji'; font-size: 1.125rem; font-weight: 600; line-height: 1.5rem; padding: .75rem 1.2rem; text-align: center; text-decoration: none #6B7280 solid; text-decoration-thickness: auto; transition-duration: .2s; transition-property: background-color,border-color,color,fill,stroke; transition-timing-function: cubic-bezier(.4, 0, 0.2, 1); user-select: none; -webkit-user-select: none; touch-action: manipulation; width: auto;">Share - اشتراک گذاری</button>

<img src="https://github.com/dev-onetv/dev-onetv.github.io/raw/main/images/webpage_qr_code.png" alt="QR Code to Scan - کد کیو آر برای اسکن" style="width:300px;"/>

<!-- ![QR Code to Scan - کد کیو آر برای اسکن](https://github.com/dev-onetv/dev-onetv.github.io/raw/main/images/webpage_qr_code.png) -->


### **Download OneElevate TV - دانلود**

*   [Google Play - گوگل پلی](https://play.google.com/store/apps/details?id=com.kamal.androidtv)
*   [Direct Download - دانلود مستقیم](https://github.com/dev-onetv/dev-onetv.github.io/raw/main/releases/OneTV_Release_35_0.apk)
*   [Amazon App Store - آمازون آپ استور](https://www.amazon.com/developer-onetv-gmail-com-OneTV-Persian-TV/dp/B09T2L7GN1)
*   [ApkPure - ای پی کی پیور](https://apkpure.com/OneTV-persian-tv/com.kamal.androidtv/download)
