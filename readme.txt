
/*Our team CSS edits*/

body{
    background-color: #eee;
    font-family: "Century Gothic";
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
}


.title{
    text-align: center;
    text-transform: capitalize;
    color: #726a95;
    margin: 10px 0;
    position: relative;
}

.title::after{
    content: "";
    position: absolute;
    width: 20%; height: 2px;
    background-image: linear-gradient(to left, transparent 5%, #726a95);
    bottom: -10px; left: 50%;
    transform: translate(-50%);
}

.team-row{
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    padding: 40px 0;
}

.member{
    flex: 1 1 250px;
    margin: 20px;
    text-align: center;
    padding: 20px 10px;
    cursor: pointer;
    max-width: 300px;
    transition: all 0.3s;
}

.member:hover{
    box-shadow: 0 10px 20px rgba(0,0,0,0.1);
    transform: translateY(-20px);
}

.member img{
    display: block;
    width: 150px; height: 150px;
    object-fit: cover;
    border:4px solid #726a95;
    border-radius: 50%;
    margin: 0 auto;
}

.member h2{
    text-transform: uppercase;
    font-size: 24px;
    color: #726a95;
    margin: 15px 0;
}

.member p{
    font-size: 15px;
    color: #838383;
    line-height: 1.6;
}

/*	Upload file styling*/

@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@200;300;400;500;600;700&display=swap');
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Poppins", sans-serif;
}
body{
  display: flex;
  align-items: center;
  justify-content: center;
  min-height: 100vh;
  background: #be9de4;
}
.drag-area{
  border: 2px dashed #fff;
  height: 500px;
  width: 700px;
  border-radius: 5px;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
}
.drag-area.active{
  border: 2px solid #fff;
}
.drag-area .icon{
  font-size: 100px;
  color: #fff;
}
.drag-area header{
  font-size: 30px;
  font-weight: 500;
  color: #fff;
}
.drag-area span{
  font-size: 25px;
  font-weight: 500;
  color: #fff;
  margin: 10px 0 15px 0;
}
.drag-area button{
  padding: 10px 25px;
  font-size: 20px;
  font-weight: 500;
  border: none;
  outline: none;
  background: #fff;
  color: #614597;
  border-radius: 5px;
  cursor: pointer;
}
.drag-area img{
  height: 100%;
  width: 100%;
  object-fit: cover;
  border-radius: 5px;
}