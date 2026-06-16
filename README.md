# front-end-Journey-5-Flex-box-Practice-basic
Here i have used flex box and played around with some elements

<img width="1020" height="977" alt="boxes flex box basic" src="https://github.com/user-attachments/assets/da93cea3-b889-4d0e-bca9-1ee5e0704ead" />

`.main {
  border: 1px solid black;
  background-color: aliceblue;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  margin: 0px 0px 30px 0px;
}`

### container

#### Here i have a conatiner which house the nav bar and the buttons
-using display flex property and valure i have gained granular control of  the elements in this class called conatiner.
- Using display flex i have now made items inline instead of block which is the default.
- Using justify-content i control the x-axis: The horizontal plane 
- Using the align-item i control the vertical axis(y):vertical plane.

`.container {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  border: 2px solid red;
  border-radius: 30px;
}`

`.navbar {
  list-style: none;
  display: flex;
  justify-content: space-around;
  gap: 30px;
  font-size: 20px;
}
.navbar a {
  text-decoration: none;
  border: 1px solid red;
  border-radius: 20px;
  padding: 10px;
}

.btns-section {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 30px;
}`



`.boxes {
  border: 10px solid red;
  margin: 20px;
  height: 300px;
  flex-wrap: wrap;
  display: flex;
  justify-content: left;
  align-items: end;
  padding: 30px;
}`
