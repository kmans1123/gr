//코드

function base() {
  translate(-350,-250);
  background(0,200,255);
  //중앙 (350,200,100,100)
  fill(255,255,255); //하얀
  ellipse(375,143,30,80); //오른 귀 흰색
  fill(241,200,196); //분홍
  ellipse(375,163,14,90); //오른 귀 분홍
  fill(255,255,255); //하얀
  ellipse(325,143,30,80); //왼쪽 귀 흰색
  fill(241,200,196); //분홍
  ellipse(325,163,14,90); //왼쪽 귀 분홍
  fill(249,211,2); //노랑
  ellipse(322,259,35,80); //왼쪽 팔
  fill(249,211,2); //노랑
  ellipse(382,259,35,80); //오른 팔
  fill(249,211,2); //노랑
  rect(325, 258, 19, 70, 20); //왼쪽 발
  fill(249,211,2); //노랑
  rect(360, 258, 19, 70, 20); //오른 발
  fill(255,255,255); //하얀
  rect(315, 234, 75, 70, 20); //몸통
  fill(255,255,255); //하얀
  ellipse(350,200,115,120); //흰 색 머리
  fill(249,211,2); //노랑
  ellipse(350,200,100,100); //노란색 얼굴
  fill(255,255,255); //하얀
  ellipse(325,197,36,20); //왼 눈 흰자
  fill(255,255,255); //하얀
  ellipse(375,197,36,20); //오른 눈 흰자
  fill(0,0,0); //검정
  ellipse(350,213,12,10); //코
  fill(0,0,0); //검정
  ellipse(324,197,7,7); //왼쪽 눈동자
  fill(0,0,0); //검정
  ellipse(374,197,7,7); //오른쪽 눈동자
  fill(249,211,2); //노랑
  arc(341.5,218,18, 20, 0, PI); //입 왼쪽
  fill(249,211,2); //노랑
  arc(358.5,218,18, 20, 0, PI); //입 오른쪽
}
function setup() {
  createCanvas(800, 800); 
  stroke(1); 
  strokeWeight(2.2);
}
function draw() {
  translate(mouseX,mouseY);
  //scale();
  base();
}

<img width="1509" alt="스크린샷 2023-03-09 오후 7 39 53" src="https://user-images.githubusercontent.com/119734977/223999791-c4b0df32-f519-4c39-b9f8-eaa7635cbbf1.png">
