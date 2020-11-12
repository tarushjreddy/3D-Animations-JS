* {
  margin: 0px;
  padding: 0;
  box-sizing: border-box;
  transition: all 0.75s ease-out;
}
body {
  font-family: "Poppins", sans-serif;
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  perspective: 1000px;
  transition: all 0.75s ease-out;
}
.container {
  /* background-color: rgb(72, 179, 250); */
  transition: all 0.05s ease-in-out;
  width: 50%;

  display: flex;
  justify-content: center;
  align-items: center;
  transition: all 0.75s ease-out;
}
.card {
  transition: all 0.5s ease-in-out;
  transform-style: preserve-3d;
  min-height: 88vh;
  width: 35rem;
  transition: all 0.75s ease-out;
  /* background-color: lightcoral; */
  border-radius: 20px;
  padding: 0rem 5rem;
  box-shadow: 0 20px 20px rgba(0, 0, 0, 0.2), 0px 0px 50px rgba(0, 0, 0, 0.2);
}
.shoe {
  display: flex;
  min-height: 25rem;
  transition: all 0.75s ease-out;
  justify-content: center;
  align-items: center;
  transition: all 0.75s ease-out;
  /* background-color: lightcoral; */
}
.shoe > img {
  width: 15rem;
  z-index: 2;
  transition: all 0.75s ease-out;
}
.circle {
  height: 15rem;
  width: 15rem;
  background: linear-gradient(
    to bottom,
    rgba(245, 70, 66, 0.75),
    rgba(8, 83, 156, 0.75)
  );
  position: absolute;
  border-radius: 300px;
  z-index: 1;
  transition: all 0.75s ease-out;
}
.title {
  transform-style: preserve-3d;
  transition: all 0.75s ease-out;
}
.informantion > h1 {
  font-size: 1.3rem;

  /* text-shadow: 2px 2px 10px black; */
  padding: 2rem 0rem;
  color: #585855;
  font-weight: bold;

  transition: all 0.5s ease-in-out;
  transition: all 0.75s ease-out;
  /* transform: translateZ(100px); */
}
h3 {
  font-size: 1.3rem;
  padding: 0.2rem 0rem;
  margin-bottom: 1.2rem;
  color: #585855;
  font-weight: lighter;
  transition: all 0.75s ease-out;
}
.sizes {
  display: flex;
  justify-content: space-between;
  transition: all 0.75s ease-out;
}
.sizes > button {
  padding: 0.5rem 2rem;
  background: none;
  border: none;
  box-shadow: 0px 5px 10px rgba(0, 0, 0, 0.2);
  border-radius: 20px;
  cursor: pointer;
  outline: none;
  transition: all 0.75s ease-out;
}
.sizes > button.active {
  background-color: lightcoral;
  color: white;
  transition: all 0.75s ease-out;
}
.sizes > button :hover {
  background-color: lightcoral;
  color: white;
  transition: all 0.75s ease-out;
}
.purchases {
  margin-top: 5rem;
  transition: all 0.75s ease-out;
}
.purchases > button {
  padding: 1rem 0rem;
  width: 100%;
  background-color: #f54642;
  color: white;
  height: 2.9rem;
  border-radius: 30px;
  box-shadow: 0px 5px 10px rgba(0, 0, 0, 0.2);
  cursor: pointer;
  outline: none;
  cursor: pointer;
  font-weight: bold;
  border: none;
  transition: all 0.75s ease-out;
}
button.active {
  background: lightpink;
}
