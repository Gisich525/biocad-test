# biocad-test
Conditions:

Table 1 shows data from the analytical instrument.
- Each sample (Sample) was measured several times (Replicate);
- For each measurement, the following data were obtained: the total number of cells in the sample (Total), the number of cells in subpopulation A (SubA), and the number of cells in subpopulation B (SubB).
- Subpopulations A (SubA) and B (SubB) do not intersect.
Table 1. Example of data from an analytical instrument

| Sample | Replicate	| Total	| SubA	| SubB |
| ------ | ---------- | ----- | ----  | ---- |
| 001 |	rep 1 |	84795	| 10003	| 258 |
| 001	| rep 2	| 85302	| 10008	| 258 |
| 001	| rep 3	| 84507	| 10006	| 252 |
| 002	| rep 1	| 75061	| 10984	| 779 |
| 002	| rep 2	| 74208	| 11007	| 760 |
| 002	| rep 3	| 73866	| 11033	| 740 |
| 003	| rep 1	| 34590	| 9720	| 169 |
| 003	| rep 2	| 30936	| 9705	| 150 |
| 003	| rep 3	| 31364	| 9697	| 142 |
| 005	| rep 1	| 24872	| 10282	| 976 |
| 005	| rep 2	| 24386	| 10290	| 1086|
| 005	| rep 3	| 24328	| 10253	| 1057|
| 007	| rep 1	| 47286	| 8127	| 327 |
| 007	| rep 2	| 52703	| 8928	| 377 |
| 007	| rep 3	| 53619	| 9530	| 401 |
| 008	| rep 1	| 29578	| 10529	| 4001 |
| 008	| rep 2	| 29352	| 7556	| 3368 |
| 008	| rep 3	| 28819	| 10479	| 4041 |
| 009	| rep 1	| 139774	| 9875	| 463 |
| 009	| rep 2	| 115865	| 8174	| 431 |
| 009	| rep 3	| 128105	| 9107	| 435 |
| 010	| rep 1	| 94601	| 10000	| 1057 |
| 010	| rep 2	| 92189	| 10000	| 991 |
| 010	| rep 3	| 89044	| 10000	| 983 |
| 013	| rep 1	| 62864	| 12673	| 355 |
| 013	| rep 2	| 63236	| 12593	| 325 |
| 013	| rep 3	| 60920	| 12123	| 329 |
| 014	| rep 1	| 38746	| 9730	| 1775 |
| 014	| rep 2	| 39418	| 9926	| 1898 |
| 014	| rep 3	| 39583	| 9824	| 1750 |

Task:
Write a script in Python that:
- accepts as input a table in any format of the candidate’s choice;
- calculates the average value and coefficient of variation of the percentage of population A;
- calculates the average value and coefficient of variation of the percentage of population B;
- calculates the average value and coefficient of variation of the percentage of a population of cells that are not included in either population A or population B (this population can be called SubC);
- saves calculations in one table.
