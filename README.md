# cs401-dissertation

This report details a project aimed at facilitating the transition from Java Development Kit (JDK) 8 to the
modular system of JDK 9 by optimizing the organization of Java import statements. Initiated by Professor
Hasan Sözer, the project employs a custom-built tool, the ‘ImportClusterer’, to restructure legacy Java code
to align with JDK 9’s modular design. We developed a methodology that parses Java files to extract import
statements, which are then analyzed and clustered by our algorithm based on their usage frequency.. Our
second algorithm, called Matrix Clustering, utilizes a co-occurrence matrix for clustering. We added
‘KModesClustering’ algorithm and a ‘Genetic Clustering Algorithm’ to be able to compare our algorithms
optimality using The &#39;MoJo metric. Using Java Swing, we implemented a GUI to enhance usability, and with
Graphviz, we can generate cluster graphs for visualization. The goal of our project is to enhance the
maintainability and scalability of Java applications as they transition to a modular system, with further
validation and optimization of the tool planned for future work.
