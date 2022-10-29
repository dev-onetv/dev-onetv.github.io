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

1. [Google Play - گوگل پلی](https://play.google.com/store/apps/details?id=com.kamal.androidtv){:target="_blank"}

2. [Directt Download - دانلود مستقیم](https://github.com/dev-onetv/dev-onetv.github.io/raw/main/releases/OneTV_Release_30_0.apk){:target="_blank"}

3. [Amazon App Store - آمازون آپ استور](https://www.amazon.com/developer-onetv-gmail-com-OneTV-Persian-TV/dp/B09T2L7GN1){:target="_blank"}

4. [APKCombo - ای پی کی کمبو](https://apkcombo.com/onetv-persian-tv/com.kamal.androidtv/){:target="_blank"}

5.  [Myket - مایکت](https://myket.ir/app/com.kamal.androidtv){:target="_blank"}

# Share - به اشتراک گذاشتن
1. <button id='share-button' onclick="shareFunction()" style="border: none; background: none;">Share - اشتراک گذاری</button>
2. QR Code - کد کیو آر
  ![QR Code to Scan - کد QR برای اسکن](https://github.com/dev-onetv/dev-onetv.github.io/raw/main/images/webpage_qr_code.png)
