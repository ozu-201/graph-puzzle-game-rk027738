cmake_minimum_required(VERSION 3.25)
project(graph_puzzle_game_rk027738)

set(CMAKE_CXX_STANDARD 14)

include_directories(201-DataStructures-CPP-master/src/Array)
include_directories(201-DataStructures-CPP-master/src/Array/DartsGame)
include_directories(201-DataStructures-CPP-master/src/Array/Graph)
include_directories(201-DataStructures-CPP-master/src/Array/Heap)
include_directories(201-DataStructures-CPP-master/src/Array/MathematicalExpression)
include_directories(201-DataStructures-CPP-master/src/Array/Sort)
include_directories(201-DataStructures-CPP-master/src/General)
include_directories(201-DataStructures-CPP-master/src/List)
include_directories(201-DataStructures-CPP-master/src/List/Graph)
include_directories(201-DataStructures-CPP-master/src/List/Polynomial)
include_directories(201-DataStructures-CPP-master/src/Tree)
include_directories(201-DataStructures-CPP-master/Test)

add_executable(graph_puzzle_game_rk027738
        201-DataStructures-CPP-master/src/Array/DartsGame/Element.cpp
        201-DataStructures-CPP-master/src/Array/DartsGame/Element.h
        201-DataStructures-CPP-master/src/Array/DartsGame/Queue.cpp
        201-DataStructures-CPP-master/src/Array/DartsGame/Queue.h
        201-DataStructures-CPP-master/src/Array/DartsGame/State.cpp
        201-DataStructures-CPP-master/src/Array/DartsGame/State.h
        201-DataStructures-CPP-master/src/Array/DartsGame/Test.cpp
        201-DataStructures-CPP-master/src/Array/Graph/Graph.cpp
        201-DataStructures-CPP-master/src/Array/Graph/Graph.h
        201-DataStructures-CPP-master/src/Array/Heap/DHeap.cpp
        201-DataStructures-CPP-master/src/Array/Heap/DHeap.h
        201-DataStructures-CPP-master/src/Array/Heap/Heap.cpp
        201-DataStructures-CPP-master/src/Array/Heap/Heap.h
        201-DataStructures-CPP-master/src/Array/Heap/HeapNode.cpp
        201-DataStructures-CPP-master/src/Array/Heap/HeapNode.h
        201-DataStructures-CPP-master/src/Array/Heap/MaxDHeap.cpp
        201-DataStructures-CPP-master/src/Array/Heap/MaxDHeap.h
        201-DataStructures-CPP-master/src/Array/Heap/MaxHeap.cpp
        201-DataStructures-CPP-master/src/Array/Heap/MaxHeap.h
        201-DataStructures-CPP-master/src/Array/Heap/MinDHeap.cpp
        201-DataStructures-CPP-master/src/Array/Heap/MinDHeap.h
        201-DataStructures-CPP-master/src/Array/Heap/MinHeap.cpp
        201-DataStructures-CPP-master/src/Array/Heap/MinHeap.h
        201-DataStructures-CPP-master/src/Array/MathematicalExpression/Element.cpp
        201-DataStructures-CPP-master/src/Array/MathematicalExpression/Element.h
        201-DataStructures-CPP-master/src/Array/MathematicalExpression/Evaluate.cpp
        201-DataStructures-CPP-master/src/Array/MathematicalExpression/Stack.cpp
        201-DataStructures-CPP-master/src/Array/MathematicalExpression/Stack.h
        201-DataStructures-CPP-master/src/Array/MathematicalExpression/Token.cpp
        201-DataStructures-CPP-master/src/Array/MathematicalExpression/Token.h
        201-DataStructures-CPP-master/src/Array/MathematicalExpression/TokenType.h
        201-DataStructures-CPP-master/src/Array/Sort/BubbleSort.cpp
        201-DataStructures-CPP-master/src/Array/Sort/BubbleSort.h
        201-DataStructures-CPP-master/src/Array/Sort/BucketSort.cpp
        201-DataStructures-CPP-master/src/Array/Sort/BucketSort.h
        201-DataStructures-CPP-master/src/Array/Sort/HeapSort.cpp
        201-DataStructures-CPP-master/src/Array/Sort/HeapSort.h
        201-DataStructures-CPP-master/src/Array/Sort/InsertionSort.cpp
        201-DataStructures-CPP-master/src/Array/Sort/InsertionSort.h
        201-DataStructures-CPP-master/src/Array/Sort/MergeSort.cpp
        201-DataStructures-CPP-master/src/Array/Sort/MergeSort.h
        201-DataStructures-CPP-master/src/Array/Sort/QuickSort.cpp
        201-DataStructures-CPP-master/src/Array/Sort/QuickSort.h
        201-DataStructures-CPP-master/src/Array/Sort/SelectionSort.cpp
        201-DataStructures-CPP-master/src/Array/Sort/SelectionSort.h
        201-DataStructures-CPP-master/src/Array/Sort/ShellSort.cpp
        201-DataStructures-CPP-master/src/Array/Sort/ShellSort.h
        201-DataStructures-CPP-master/src/Array/Sort/Sort.h
        201-DataStructures-CPP-master/src/Array/DisjointSet.cpp
        201-DataStructures-CPP-master/src/Array/DisjointSet.h
        201-DataStructures-CPP-master/src/Array/Element.cpp
        201-DataStructures-CPP-master/src/Array/Element.h
        201-DataStructures-CPP-master/src/Array/Hash.cpp
        201-DataStructures-CPP-master/src/Array/Hash.h
        201-DataStructures-CPP-master/src/Array/Queue.cpp
        201-DataStructures-CPP-master/src/Array/Queue.h
        201-DataStructures-CPP-master/src/Array/Set.cpp
        201-DataStructures-CPP-master/src/Array/Set.h
        201-DataStructures-CPP-master/src/Array/Stack.cpp
        201-DataStructures-CPP-master/src/Array/Stack.h
        201-DataStructures-CPP-master/src/General/AbstractGraph.cpp
        201-DataStructures-CPP-master/src/General/AbstractGraph.h
        201-DataStructures-CPP-master/src/General/Path.cpp
        201-DataStructures-CPP-master/src/General/Path.h
        201-DataStructures-CPP-master/src/List/Graph/Edge.cpp
        201-DataStructures-CPP-master/src/List/Graph/Edge.h
        201-DataStructures-CPP-master/src/List/Graph/EdgeList.cpp
        201-DataStructures-CPP-master/src/List/Graph/EdgeList.h
        201-DataStructures-CPP-master/src/List/Graph/Graph.cpp
        201-DataStructures-CPP-master/src/List/Graph/Graph.h
        201-DataStructures-CPP-master/src/List/Polynomial/Polynomial.cpp
        201-DataStructures-CPP-master/src/List/Polynomial/Polynomial.h
        201-DataStructures-CPP-master/src/List/Polynomial/Term.cpp
        201-DataStructures-CPP-master/src/List/Polynomial/Term.h
        201-DataStructures-CPP-master/src/List/Polynomial/TermNode.cpp
        201-DataStructures-CPP-master/src/List/Polynomial/TermNode.h
        201-DataStructures-CPP-master/src/List/Polynomial/TestPolynomial.cpp
        201-DataStructures-CPP-master/src/List/DoublyLinkedList.cpp
        201-DataStructures-CPP-master/src/List/DoublyLinkedList.h
        201-DataStructures-CPP-master/src/List/DoublyNode.cpp
        201-DataStructures-CPP-master/src/List/DoublyNode.h
        201-DataStructures-CPP-master/src/List/Hash.cpp
        201-DataStructures-CPP-master/src/List/Hash.h
        201-DataStructures-CPP-master/src/List/LinkedList.cpp
        201-DataStructures-CPP-master/src/List/LinkedList.h
        201-DataStructures-CPP-master/src/List/Node.cpp
        201-DataStructures-CPP-master/src/List/Node.h
        201-DataStructures-CPP-master/src/List/Queue.cpp
        201-DataStructures-CPP-master/src/List/Queue.h
        201-DataStructures-CPP-master/src/List/Stack.cpp
        201-DataStructures-CPP-master/src/List/Stack.h
        201-DataStructures-CPP-master/src/Tree/AvlTree.cpp
        201-DataStructures-CPP-master/src/Tree/AvlTree.h
        201-DataStructures-CPP-master/src/Tree/AvlTreeNode.cpp
        201-DataStructures-CPP-master/src/Tree/AvlTreeNode.h
        201-DataStructures-CPP-master/src/Tree/BTree.cpp
        201-DataStructures-CPP-master/src/Tree/BTree.h
        201-DataStructures-CPP-master/src/Tree/BTreeNode.cpp
        201-DataStructures-CPP-master/src/Tree/BTreeNode.h
        201-DataStructures-CPP-master/src/Tree/Element.cpp
        201-DataStructures-CPP-master/src/Tree/Element.h
        201-DataStructures-CPP-master/src/Tree/Queue.cpp
        201-DataStructures-CPP-master/src/Tree/Queue.h
        201-DataStructures-CPP-master/src/Tree/Stack.cpp
        201-DataStructures-CPP-master/src/Tree/Stack.h
        201-DataStructures-CPP-master/src/Tree/Tree.cpp
        201-DataStructures-CPP-master/src/Tree/Tree.h
        201-DataStructures-CPP-master/src/Tree/TreeNode.cpp
        201-DataStructures-CPP-master/src/Tree/TreeNode.h
        201-DataStructures-CPP-master/Test/catch.hpp
        201-DataStructures-CPP-master/Test/LinkedListTest.cpp 201-DataStructures-CPP-master/src/Main.cpp 201-DataStructures-CPP-master/src/Main.h)
