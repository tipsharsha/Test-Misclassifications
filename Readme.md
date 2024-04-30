
#Path: Tree Diagrams
    Decision Tree Diagrams for the Misclassification Clusters
    The Decision Tree Diagrams are generated using the DecisionTreeClassifier from the sklearn library
    The Decision Tree Diagrams are generated using the Graphviz library
    The Decision Tree Diagrams are generated using the pydot library

    University1
    University2
    IT

    Each Image with the name of the changes 
    Leaf nodes give the Misclassification count 
    Color of the nodes to be ignored
dot -Tpng tree.dot -o tree.png
    

#Path: Misclassification Clusters
    Data:
    Total Train Data: Count of Cluster vs Dataset with Different Strategies
    Misclassification Count: Count of Misclassification vs Dataset with Different Strategies

    Plots:
    Misclassification Count vs Cluster
    Train Data vs Cluster for showing proper seperation
    