<script>
function myFunction() {
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
<button id='answer-example-share-button' onclick="myFunction()">Share!</button>
