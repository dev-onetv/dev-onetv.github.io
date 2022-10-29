<script>
function shareFunction() {
  if (navigator.share) {
    navigator.share({
        title: 'Checkout "OneTV - Persian TV"',
        text: 'Checkout "OneTV - Persian TV"',
        url: 'https://dev-onetv.github.io/',
      })
      .catch((error) => console.log('Error sharing', error));
  } else {
    var email = 'sample@gmail.com';
    var subject = 'Checkout "OneTV - Persian TV"';
    var emailBody = 'Checkout "OneTV - Persian TV" at: https://dev-onetv.github.io/';
    document.location = "mailto:?subject="+subject+"&body="+emailBody;
  }
}
</script>

<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>


# Download - دانلود

*   [Google Play - گوگل پلی](https://play.google.com/store/apps/details?id=com.kamal.androidtv){:target="_blank"}

*   [Directt Download - دانلود مستقیم](https://github.com/dev-onetv/dev-onetv.github.io/raw/main/releases/OneTV_Release_30_0.apk){:target="_blank"}

*   [Amazon App Store - آمازون آپ استور](https://www.amazon.com/developer-onetv-gmail-com-OneTV-Persian-TV/dp/B09T2L7GN1){:target="_blank"}

*   [APKCombo - ای پی کی کمبو](https://apkcombo.com/onetv-persian-tv/com.kamal.androidtv/){:target="_blank"}

*   [Myket - مایکت](https://myket.ir/app/com.kamal.androidtv){:target="_blank"}

# Share - به اشتراک گذاشتن
*   <button id='share-button' onclick="shareFunction()" style="border: none; background: none; color: #0000EE; font-size: large">Share - اشتراک گذاری</button>
*   QR Code - کد کیو آر

![QR Code to Scan - کد QR برای اسکن](https://github.com/dev-onetv/dev-onetv.github.io/raw/main/images/webpage_qr_code.png)
