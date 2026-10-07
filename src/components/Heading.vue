<template>
  <section class= "hero">

    <div class= "lefttext">
    <h4> ——— ESTABLISHED 1905 </h4>
      <h1>
        Exemplary <br> <i>Christian</i></br>
        <br>
        Education for <br> Life. </br>
      </h1>
      <br><div class= "line1" > </div>

      <p>
        A leading Christian institution in the Philippines,
        Central <br>Philippine University nurtures intellectual
        growth and <br>spiritual development through a commitment
        to <b>Scientia et<br> Fides</b> </br>(Science and Faith).
      </p>

      <div class= "buttons">
        <button class= "b1">
          Explore Academics
        </button>

        <button class= "b2">
          Request Information
        </button>
      </div>
      <div class="card1">
        <div class="stats">
        <h2>118+</h2>
        <p>Years of Excellence</p>
        </div>
        <div class="stats">
        <h2>20+</h2>
        <p>Academic Progress</p>
      </div>
      <div class="stats">
        <h2>5,000+</h2>
        <p>Active Students</p>
      </div>
      <div class="stats">
        <h2>20+</h2>
        <p>Partner institution</p>
      </div>
      </div>
    </div>

    <div class= "right">

      <div class= "card">

        <img src= "@/assets/cpu_logo_seal.png" alt="logo">

        <h2> Chicago Freestyle University </h2>

        <h4> SCIENTIA ET FIDES </h4>

        <div class= "line2" > </div>

        <p> "A Heritage of Excellence,<br> A Future of Faith" </p>
      </div>

    </div>

  </section>
</template>

<style scoped>
.hero{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:70px 60px;
    background:#f7f7f7;
    margin-left: 200px;
    margin-right: 200px;
}

.lefttext{
    width:50%;
}

.lefttext h4{
    color:#C8A100;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-weight:795;
    margin-bottom: -25px;

}

.lefttext h1{
    font-size:60px;
    color:#34136d;
    line-height:50px;
    margin-bottom:5px;
}

.lefttext p{
    font-size:22px;
    line-height:30px;
    color:#34136d;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

.lefttext i{
    color:#C8A100;
}

.buttons{
    margin-top:35px;
    display:flex;
    gap:20px;
}

.b1{
    background:#34136d;
    color:white;
    padding:18px 30px;
    border:none;
    border-radius:6px;
    cursor:pointer;
    font-weight: bold;
}

.b2{
    background:white;
    border:2px solid #34136d;
    padding:18px 30px;
    border-radius:7px;
    cursor:pointer;
    color: #34136d;
    font-weight: bold;
}

.right{
    width:40%;
    position:relative;
    display:flex;
    justify-content:center;
}



.card{
    position:relative;
    background: linear-gradient(135deg, #C8A100, #FFFFFF);
    width:700px;
    height:750px;
    border-radius:15px;
    display:flex;
    flex-direction:column;
    justify-content:center;
    align-items:center;
    box-shadow:0 8px 20px rgba(0,0,0,.15);

}

.card1{
    margin-top:30px;
    grid-template-columns: repeat(4, 1fr);
    padding: 1.5rem;
    border-radius:12px;
    display:grid;
    background: #FFFFFF;
    box-shadow:0 8px 20px rgba(0,0,0,0.03);
    border: 1px solid #FFFFFF;
}

.stats p{
    text-align: center;
    border-right: 1px solid #FFFFFF;
    font-size: 17px;
}

.stats {
    text-align: center;
    border-right: 1px solid #FFFFFF;
}

.stats h2 {
    margin: 0 0 4px 0;
    color: #482080;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;

}

.card img{
    width:170px;
    margin-bottom:20px;
}

.card h2{
    text-align:center;
    font-size:45px;
    color:#34136d;
    font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;

}

.card h4{
    margin-top:-25px;
    color:#8d7318;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    letter-spacing: 4px;
}

.line0{
    width:50px;
    height:2px;
    background:#C8A100;
 
}

.line1{
    width:70px;
    height:2px;
    background:#C8A100;
    margin:25px 0;
}

.line2{
    width:80px;
    height:2px;
    background:#C8A100;
    margin:25px 0;
}




.card p{
    font-weight:450;
    font-size:20px;
    text-align:center;
    font-style:italic;
    color:#34136d;
    font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
</style>