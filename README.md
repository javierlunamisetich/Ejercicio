La notebook ejercicio.ipynb contiene la función kmeans(data, k, initial_centroids, maxiter) donnde
  data: numpy.array bidimensional con cada dato puesto como fila
  k: elección de número de clusters
  initial_centroids: elección inicial de los centroides.
  maxiter: máximo número de iteraciones
  
Esta función arroja como output "centroids, cluster_assignment"
  centroids: array con las coordenadas de los k centros de los clusters calculados
  cluster_assignment: array que contiene el cluster asignado para cada dato


Esta función utiliza dos funciones auxiliares: "assign_clusters", que asigna cada dato a su centro más cercano, y "revise_centroids", que calcula los nuevos centros para cada iteración. 

Para utilizar el programa, la funcion "initialize_cluster_centers" elige k datos de forma aleatoria, que pueden ser utilizados como el input "initial_centroids" de la función principal "kmeans". Luego se llama "kmeans". 

La sección "Testing with fabricated data" se encuentra un ejemplo de cómo usar los algoritmos y se provee de la función "createClusteredData(N, k)" que permite crear N datos centrados en k clusters gaussianos para probar el algoritmo.



