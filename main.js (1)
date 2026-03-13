function openCard() {
  document.getElementById("intro").classList.add("hidden");
  document.getElementById("card").classList.remove("hidden");
  document.querySelector(".card-page").classList.add("show");
  typeMessage();
}
function showVideo() {
  document.getElementById("videoFrame").classList.remove("hidden");
}

const messageText = 'Dearest Suparna, from the starting of class 8 to literally the end of class 10 where we are literally giving our boards,3 YEARS WOOHOO, thankyou for being there for me during my ups and downs and being the ever supportive and awesome friend you are.We have made so many memories as well as fights and i hope we can make more in the upcoming years.I could never ask for a better friend than you are so thankyou again for being such a huge part of my life. So, Happy Sixteenth iloveyousm.i know boards are going on so thik sweet holona but we ball and i aint calling you didi thikache';
let i = 0;

function typeMessage() {
  if (i < messageText.length) {
    document.getElementById("typedMessage").innerHTML += messageText.charAt(i);
    i++;
    setTimeout(typeMessage, 35);
  }
  else {
    document.getElementById("revealBtn").style.display = "block";
  }
}
