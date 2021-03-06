Problem

Given a grid of R rows and C columns each cell in the grid is either 0 or 1.
A segment is a nonempty sequence of consecutive cells such that all cells are in the same row or the same column. We define the length of a segment as number of cels in the sequence.
A segment is called "good" if all the cells in the segment contain only 1s.
An "L-shape" is defined as an unordered pair of segments, which has all the following properties:
Each of the segments must be a "good" segment.
The two segments must be perpendicular to each other.
The segments must share one cell that is an endpoint of both segments.
Segments must have length at least 2.
The length of the longer segment is twice the length of the shorter segment.
We need to count the number of L-shapes in the grid.

Below you can find two examples of correct L-shapes,and three examples of invalid L-Shapes.

https://codejam.googleapis.com/dashboard/get_file/AQj_6U2rdoxtGv0G9CaXcXgdGRdUDpiQ7aGh94KOMrHoHeX6YFw7yoHg8nDzN372AfJ7MtJpOh7DcqGMe0E/examples_correct.png

https://codejam.googleapis.com/dashboard/get_file/AQj_6U2I5Y9CuUF0pq4G5PQEpqO8HjkpKTEfGMRJcx0zF8tB6uHXSabAlVHhmTwdoVPq8_aBbaTp1vfZwjTkoA/examples_incorrect.png

Note

That in the shape on the left, two segments do not share a common endpoint. The next two shapes do not meet the last requirement, as in the middle shape both segments have the same length, and in the last shape the longer segment is longer than twice the length of the shorter one.

Input

The first line of the input contains the number of test cases, T. T test cases follow.
The first line of each testcase contains two integers R and C.
Then, R lines follow, each line with C integers representing the cells of the grid.

Output

For each test case, output one line containing Case #x: y, where x is the test case number (starting from 1) and y is the number of L-shapes.

Sample Input

2
4 3
1 0 0
1 0 1
1 0 0
1 1 0
6 4
1 0 0 0
1 0 0 1
1 1 1 1
1 0 1 0
1 0 1 0
1 1 1 0


Sample Output

Case #1: 1
Case #2: 9

