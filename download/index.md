<script>
function shareFunction() {
  if (navigator.share) {
    navigator.share({
        title: 'Web Share API Draft',
        text: 'Take a look at this spec!',
        url: 'https://wicg.github.io/web-share/#share-method',
      })
      .then(() => console.log('Successful share'))
      .catch((error) => console.log('Error sharing', error));
  } else {
    console.log('Share not supported on this browser, do it the old way.');
    var email = 'sample@gmail.com';
    var subject = 'Test';
    var emailBody = 'Hi Sample,';
    var attach = 'path';
    document.location = "mailto:"+email+"?subject="+subject+"&body="+emailBody;
  }
}
</script>

<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>


# Download - دانلود

 ### [Google Play - گوگل پلی](https://play.google.com/store/apps/details?id=com.kamal.androidtv){:target="_blank"}
 ### [Directt Download - دانلود مستقیم](https://github.com/dev-onetv/dev-onetv.github.io/raw/main/releases/OneTV_Release_30_0.apk){:target="_blank"}
 ### [Amazon App Store - آمازون آپ استور](https://www.amazon.com/developer-onetv-gmail-com-OneTV-Persian-TV/dp/B09T2L7GN1){:target="_blank"}
 ### [APKCombo - ای پی کی کمبو](https://apkcombo.com/onetv-persian-tv/com.kamal.androidtv/){:target="_blank"}
 ### [Myket - مایکت](https://myket.ir/app/com.kamal.androidtv){:target="_blank"}

# Share - به اشتراک گذاشتن
1. <button id='share-button' onclick="shareFunction()">Share - اشتراک گذاری</button>
2. ![QR Code to Scan - کد QR برای اسکن](https://github.com/dev-onetv/dev-onetv.github.io/raw/main/images/webpage_qr_code.png)
