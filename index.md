<script>
function shareFunction() {
  if (navigator.share) {
    navigator.share({
        title: 'Checkout "OneTV - Persian TV"',
        text: 'Watch Persian, Kurdish (and many other languages) TV Channels Live on "OneTV - Persian TV". You can download the app at: ',
        url: 'https://dev-onetv.github.io/',
      })
      .catch((error) => console.log('Error sharing', error));
  } else {
    var email = 'sample@gmail.com';
    var subject = 'Checkout "OneTV - Persian TV"';
    var emailBody = 'Watch Persian, Kurdish (and many other languages) TV Channels Live on "OneTV - Persian TV". You can download the app at: https://dev-onetv.github.io/';
    var isWebView = navigator.userAgent.match("1") != null;
    if (! isWebView) {
      document.location = "mailto:?subject="+subject+"&body="+emailBody;
    }
  }
}
</script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>

### About OneTV

OneTV provides an interface to watch the free and publically available on the web Live TV channels in one place.

Users can add aditional channels by providing the URL to a web page that streams a publicallay available live TV channel. The channels added by a user are private to the user and will not be shared with other users.

The app is designed for great user experience by providing a smooth and fast user interface. 

OneTV can be installed on Phones, Tablets and TV devices.

The app is free!

### **Download OneTV**

*   [Google Play](https://play.google.com/store/apps/details?id=com.kamal.androidtv){:target="_blank"}

*   [Direct Download](https://github.com/dev-onetv/dev-onetv.github.io/raw/main/releases/OneTV_Release_30_0.apk){:target="_blank"}

*   [Amazon App Store](https://www.amazon.com/developer-onetv-gmail-com-OneTV-Persian-TV/dp/B09T2L7GN1){:target="_blank"}

*   [APKCombo](https://apkcombo.com/onetv-persian-tv/com.kamal.androidtv/){:target="_blank"}

*   [Myket](https://myket.ir/app/com.kamal.androidtv){:target="_blank"}


<p align="center">
  <button id='share-button' onclick="shareFunction()" style="background-color: #111827; border: 1px solid transparent; border-radius: .75rem; box-sizing: border-box; color: #FFFFFF; cursor: pointer; flex: 0 0 auto; font-family: 'Inter var',ui-sans-serif,system-ui,-apple-system,system-ui,'Segoe UI',Roboto,'Helvetica Neue',Arial,'Noto Sans',sans-serif,'Apple Color Emoji','Segoe UI Emoji','Segoe UI Symbol','Noto Color Emoji'; font-size: 1.125rem; font-weight: 600; line-height: 1.5rem; padding: .75rem 1.2rem; text-align: center; text-decoration: none #6B7280 solid; text-decoration-thickness: auto; transition-duration: .2s; transition-property: background-color,border-color,color,fill,stroke; transition-timing-function: cubic-bezier(.4, 0, 0.2, 1); user-select: none; -webkit-user-select: none; touch-action: manipulation; width: auto;">Share OneTV</button>
  
  <br/><br/>
  
  <img src="https://github.com/dev-onetv/dev-onetv.github.io/raw/main/images/webpage_qr_code.png" alt="QR Code to Scan" style="width:200px;" onclick="shareFunction()"/>
</p>


<!-- ![QR Code to Scan - کد کیو آر برای اسکن](https://github.com/dev-onetv/dev-onetv.github.io/raw/main/images/webpage_qr_code.png) -->


### **Disclaimer**

We are not providing the channels ourselves and all the channels provided on OneTV are publicly available on the Internet. To the best of our knowledge, the owners of channels intended the channels to be watched through various Internet browsers and live TV streaming interfaces, such as OneTV.

### **Request to Remove Channels**

If you are the owner of a channel and would not want the channel to be available on OneTV, please send us an email at developer.onetv@gmail.com and we will remove the channel immediately.

### **Privacy Policy**

OneTV built the OneTV app as a Free app. This SERVICE is provided by OneTV at no cost and is intended for use as is.

This page is used to inform visitors regarding our policies with the collection, use, and disclosure of Personal Information if anyone decided to use our Service.

If you choose to use our Service, then you agree to the collection and use of information in relation to this policy. The Personal Information that we collect is used for providing and improving the Service. We will not use or share your information with anyone except as described in this Privacy Policy.

The terms used in this Privacy Policy have the same meanings as in our Terms and Conditions, which are accessible at OneTV unless otherwise defined in this Privacy Policy.

**Information Collection and Use**

For a better experience, while using our Service, we may require you to provide us with certain personally identifiable information. The information that we request will be retained by us and used as described in this privacy policy.

The app does use third-party services that may collect information used to identify you.

Link to the privacy policy of third-party service providers used by the app

*   [Google Play Services](https://www.google.com/policies/privacy/)
*   [Google Analytics for Firebase](https://firebase.google.com/policies/analytics)

**Log Data**

We want to inform you that whenever you use our Service, in a case of an error in the app we collect data and information (through third-party products) on your phone called Log Data. This Log Data may include information such as your device Internet Protocol (“IP”) address, device name, operating system version, the configuration of the app when utilizing our Service, the time and date of your use of the Service, and other statistics.

**Cookies**

Cookies are files with a small amount of data that are commonly used as anonymous unique identifiers. These are sent to your browser from the websites that you visit and are stored on your device's internal memory.

This Service does not use these “cookies” explicitly. However, the app may use third-party code and libraries that use “cookies” to collect information and improve their services. You have the option to either accept or refuse these cookies and know when a cookie is being sent to your device. If you choose to refuse our cookies, you may not be able to use some portions of this Service.

**Service Providers**

We may employ third-party companies and individuals due to the following reasons:

*   To facilitate our Service;
*   To provide the Service on our behalf;
*   To perform Service-related services; or
*   To assist us in analyzing how our Service is used.

We want to inform users of this Service that these third parties have access to their Personal Information. The reason is to perform the tasks assigned to them on our behalf. However, they are obligated not to disclose or use the information for any other purpose.

**Security**

We value your trust in providing us your Personal Information, thus we are striving to use commercially acceptable means of protecting it. But remember that no method of transmission over the internet, or method of electronic storage is 100% secure and reliable, and we cannot guarantee its absolute security.

**Links to Other Sites**

This Service may contain links to other sites. If you click on a third-party link, you will be directed to that site. Note that these external sites are not operated by us. Therefore, we strongly advise you to review the Privacy Policy of these websites. We have no control over and assume no responsibility for the content, privacy policies, or practices of any third-party sites or services.

**Children’s Privacy**

These Services do not address anyone under the age of 13. We do not knowingly collect personally identifiable information from children under 13 years of age. In the case we discover that a child under 13 has provided us with personal information, we immediately delete this from our servers. If you are a parent or guardian and you are aware that your child has provided us with personal information, please contact us so that we will be able to do the necessary actions.

**Changes to This Privacy Policy**

We may update our Privacy Policy from time to time. Thus, you are advised to review this page periodically for any changes. We will notify you of any changes by posting the new Privacy Policy on this page.

This policy is effective as of 2022-04-27

**Contact Us**

If you have any questions or suggestions about our Privacy Policy, do not hesitate to contact us at developer.onetv@gmail.com.
