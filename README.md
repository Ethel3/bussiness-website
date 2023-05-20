# DummySite1
This site was made with HTML, CSS & JS

## Live Demo
Check it out at https://ethel-dummy.netlify.app

<section class="offer">
<h1>What We Offer</h1>
<p>Our first priority is the growth of our students.</p>

<div class="row"> 
    <div class="offer-col">
        <h3>Creative lessons</h3>
        <p>HTML is the standard markup language for documents designed to be displayed in a web broswer .</p>
        </div>
        <div class="offer-col">
            <h3>Happy Environment</h3>
            <p>Cascading Style Sheets is a style language used for describing the presentation of a document written in a markup language such as HTML.</p>
            </div>
            <div class="offer-col">
                <h3>Certified Teachers</h3>
                <p>Javascript, often abbreviated JS, is a programming language that is one of the core technologies of the World Wide Web, alongside HTML and CSS.</p>
                </div>
                </div>
                <div class="row"> 
                <div class="offer-col">
                    <h3>Safety first</h3>
                    <p>Javascript, often abbreviated JS, is a programming language that is one of the core technologies of the World Wide Web, alongside HTML and CSS.</p>
                    </div>
                    <div class="offer-col">
                        <h3>Small class size</h3>
                        <p>Javascript, often abbreviated JS, is a programming language that is one of the core technologies of the World Wide Web, alongside HTML and CSS.</p>
                        </div>
                        <div class="offer-col">
                            <h3>Infact Care</h3>
                            <p>Javascript, often abbreviated JS, is a programming language that is one of the core technologies of the World Wide Web, alongside HTML and CSS.</p>
                            </div>
</div>


</section>




<!-- dfghj -->
/*----- What we offer -----*/

.offer{
  width: 80%;
  margin: auto;
  text-align: center;
  padding-top: 100px;
}
h1{
  font-size: 40px;
  font-weight: 600;
}

p{
  color: #777;
  font-size: 14px;
  font-weight: 300;
  line-height: 22px;
  padding: 10px;
}

.row{
  margin-top: 5%;
  display: flex;
  justify-content: space-between;
}
.offer-col{
  flex-basis: 31%;
  background: #fff3f3;
  border-radius: 10px;
  margin-bottom: 5%;
  padding: 22px 12px;
  box-sizing: border-box;
  transition: 0.5s;
}
h3{
  text-align: center;
  font-weight: 600;
  margin: 10px 0;
}
.offer-col:hover{
  box-shadow: 0 0 20px 0px rgba(0,0,0,0.2);
}
@media(max-width: 700px){
.row{
  flex-direction: column;
}
}
/* #ffff00#f7f7f7#78853f */
