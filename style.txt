function mostrarMaterias(ciclo) {
  const div = document.getElementById(`ciclo${ciclo}`);
  div.style.display = div.style.display === "none" || div.style.display === "" ? "block" : "none";
}
