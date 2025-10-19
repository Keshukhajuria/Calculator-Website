let currentDisplay = "";

function appendValue(value) {
  currentDisplay += value;
  document.getElementById("calc-text").value = currentDisplay;
}

function clearDisplay() {
  currentDisplay = "";
  document.getElementById("calc-text").value = "";
}

function deleteLast() {
  currentDisplay = currentDisplay.slice(0, -1);
  document.getElementById("calc-text").value = currentDisplay;
}

function calculate() {
  try {
    currentDisplay = eval(currentDisplay).toString();
    document.getElementById("calc-text").value = currentDisplay;
  } catch (e) {
    document.getElementById("calc-text").value = "Error";
  }
}
