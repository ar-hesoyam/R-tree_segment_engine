# R-tree_segment_engine
Sets of segments are stored as a data structure known as the R-tree

Available commands:
  CREATE set_name;
  INSERT set_name [l, h]; // where [l, h] is a segment
  PRINT_TREE set_name; 
  CONTAINS set_name [l, h];
  SEARCH set_name *[WHERE query];
    query := CONTAINS [L, H]
 		 | INTERSECTS [L, H]
 		 | LEFT_OF x
