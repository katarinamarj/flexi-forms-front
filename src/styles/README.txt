.button-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  min-height: 50px; /* Obezbeđuje da prostor ispod dugmeta ostane isti */
  position: relative; /* Drži grešku ispod dugmeta */
}

.error {
  color: red;
  font-size: 14px;
  margin-top: 5px;
  opacity: 0;
  transition: opacity 0.3s ease-in-out;
  position: absolute;
}

.error.visible {
  opacity: 1;
}

.error.hidden {
  opacity: 0;
}
