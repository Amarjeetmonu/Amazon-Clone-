#CSS
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

header {
  background-color: #232f3e;
  color: white;
  padding: 10px 20px;
  display: flex;
  align-items: center;
  gap: 10px;
}

input {
  flex: 1;
  padding: 8px;
}

button {
  background: #ffa41c;
  border: none;
  padding: 8px 12px;
  cursor: pointer;
  border-radius: 4px;
}

main {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
  padding: 20px;
  gap: 20px;
}

.card {
  border: 1px solid #ddd;
  border-radius: 5px;
  padding: 10px;
  text-align: center;
}

.card img {
  width: 100%;
  height: 150px;
  object-fit: cover;
}

.card button {
  margin-top: 10px;
  width: 100%;
}
