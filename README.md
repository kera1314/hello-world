https://codepen.io/kera1314/pen/vqjzYx

html

  <div class="box">
  <h1>
    Dr. Norman Borlaug
  </h1>
  <p>
     The man who saved a billion lives  
  </p>
  <div class="box1">
  <img src="https://c2.staticflickr.com/4/3689/10613180113_fdf7bcd316_b.jpg" alt="scientist">
    <p>Dr. Norman Borlaug, third from left, trains biologists in Mexico on how to increase wheat yields - part of his life-long war on hunger.</p>
    </div>
    <div class="box2">
      <h2>
        Here's a time line of Dr. Borlaug's life:
      </h2>
      <ul>
        <li><span>1914</span> - Born in Cresco, Iowa</li>
        <li><span>1933</span> - Leaves his family's farm to attend the University of Minnesota, thanks to a Depression era program known as the "National Youth Administration"</li>
        <li><span>1935</span> - Has to stop school and save up more money. Works in the Civilian Conservation Corps, helping starving Americans. "I saw how food changed them", he said. "All of this left scars on me."
1937 - Finishes university and takes a job in the US Forestry Service</li>
        <li><span>1938</span> - Marries wife of 69 years Margret Gibson. Gets laid off due to budget cuts. Inspired by Elvin Charles Stakman, he returns to school study under Stakman, who teaches him about breeding pest-resistent plants.</li>
        <li><span>1941</span> - Tries to enroll in the military after the Pearl Harbor attack, but is rejected. Instead, the military asked his lab to work on waterproof glue, DDT to control malaria, disenfectants, and other applied science.</li>
        <li><span>1942</span> - Receives a Ph.D. in Genetics and Plant Pathology</li>
        <li><span>1944</span> - Rejects a 100% salary increase from Dupont, leaves behind his pregnant wife, and flies to Mexico to head a new plant pathology program. Over the next 16 years, his team breeds 6,000 different strains of disease resistent wheat - including different varieties for each major climate on Earth.</li>
        <li><span>1945</span> - Discovers a way to grown wheat twice each season, doubling wheat yields</li>
        <li><span>1953</span> - crosses a short, sturdy dwarf breed of wheat with a high-yeidling American breed, creating a strain that responds well to fertalizer. It goes on to provide 95% of Mexico's wheat.</li>
        <li><span>1962</span> - Visits Delhi and brings his high-yielding strains of wheat to the Indian subcontinent in time to help mitigate mass starvation due to a rapidly expanding population</li>
        <li><span>1970</span> - receives the Nobel Peace Prize</li>
        <li><span>1983</span> - helps seven African countries dramatically increase their maize and sorghum yields</li>
        <li><span>1984</span> - becomes a distinguished professor at Texas A&M University</li>
        <li><span>2005</span> - states "we will have to double the world food supply by 2050." Argues that genetically modified crops are the only way we can meet the demand, as we run out of arable land. Says that GM crops are not inherently dangerous because "we've been genetically modifying plants and animals for a long time. Long before we called it science, people were selecting the best breeds."</li>
        <li><span>2009</span> - dies at the age of 95.</li>
      </ul>
      <div class="box3">
        <h3>"Borlaug's life and achievement are testimony to the far-reaching contribution that one man's towering intellect, persistence and scientific vision can make to human peace and progress."</h3>
        <p>
          --Indian Prime Minister Manmohan Singh
        </p>
        <p calss="box3_p">
          If you have time, you should read more about this incredible human being on his <a href="https://en.wikipedia.org/wiki/Norman_Borlaug">Wikipedia entry.</a>
        </p>
      </div>
    </div>
  </div>
  <div class="foot">
    <p>Written and coded by <a href="https://www.freecodecamp.org/quincylarson">Quincy Larson.</a></p>
  </div>
</body>


css
body{
  margin:auto;
  width:50%;
}

.box{
  margin:0px;
  padding:0px;
  text-align:center;
  background-color:#D3D3D3;
  width:1200px;
  heigth:
}

h1 {
  font-size:50px;
}
.box1{
  position: relative;
  margin:atuo auto;
  background-color:white;
}
img{
  position:absolute;
  left:90px;
}
.box2{
  position:absolute;
  margin-top:600px;
  text-align:left;
  padding-left:150px;
}
span{
  font-weight:bold;
}

.box3_p{
  font-weight:bold;
  font-size:50px;
}

.foot{
  position:absolute;
  margin-top:1450px;
  margin-left:500px;
}
