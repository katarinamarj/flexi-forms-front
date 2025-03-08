html, body {
  margin: 0;
  padding: 0;
  height: 100%;
  overflow: hidden;
}


.container {
    display: flex;
    justify-content: center;
    align-items: center;
    background: #2c3424;
    height: 100vh;

}
    
.left-side, .right-side {
    flex: 1; 
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    color: #DADED8;

}
.left-side {
    background:#2c3424;
    align-items: center;
    padding: 20px;
    height: auto;
    transform: translateY(-60px); /* Pomeraj prema gore */

}


.left-side h1{
    font-size: 50px;
}





  .signup-btn {
    background: transparent;
    border: 2px solid#DADED8;
    color: #DADED8;
    padding: 10px 20px;
    border-radius: 20px;
    cursor: pointer;
  }
  
  .signup-btn:hover {
    background: #DADED8;
    color: #333;
  }
  
  .right-side {
    background: #4c583e;
    padding: 40px;
    height: 100%; 
   }



   .right-side h1{
    transform: translateY(-100px);
    font-size: 30px;
   }

   
  
  .login-box {
    width: 70%;
  }
  
 

  .login-box h1{
margin-bottom: 50px;  }

  .input-group {
    margin-bottom: 25px;
    transform: translateY(-100px);

  }
  

  .input-group label {
    display: block;
    margin-bottom: 10px;
    font-weight: bold;
  }
  
  .input-group input {
    width: 100%;
    padding: 10px;
    border: 1px solid #DADED8;
    border-radius: 5px;
    background-color: transparent;
    color: #DADED8;
  }
  
 
  
  .login-btn {
    background: transparent;
    border: 2px solid#DADED8;
    color: #DADED8;
    padding: 10px 20px;
    border-radius: 20px;
    cursor: pointer;
    
    transform: translateY(-90px);

  }
  
  .login-btn:hover {
    background: #DADED8;
    color: #333;

  }
  
  
  .logo {
    position: absolute;
    top: 20px;  
    left: 20px; 
    width: 100px; 
    height: 50px;
}
