The Triangulator - a java applet which animates some brute force
 * Delaunay triangulation algorithms of varying computational 
 * complexity.  
 * 
 * Author: Geoff Leach.  gl@cs.rmit.edu.au
 * Date: 29/3/96
 *
 * License to copy and use this software is granted provided that
 * appropriate credit is given to both RMIT and the author.
 *
 * The point of the applet is educational: 
 *
 * (a) To illustrate the importance of computational complexity.
 * The three Delaunay triangulation algorithms implemented have
 * computational complexities of O(n^2), O(n^3) and O(n^4).  The
 * user can see for themselves the improvement in speed going 
 * from O(n^4) to O(n^2).
 * 
 * (b) To illustrate what Delaunay triangulations are.  The Delaunay
 * triangulation, and the related Voronoi diagram, is a 
 * particularly useful data structure for a number of problems.
 * Without going into the applications the applet attempts to 
 * show what Delaunay triangulation algorithms are.
 *
 * (c) To provide a useful context for me to initially learn Java.
 *
 * The code still needs polishing ... 