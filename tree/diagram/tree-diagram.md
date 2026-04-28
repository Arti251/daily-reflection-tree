```mermaid
graph TD
START --> Q1
Q1 --> A1_Q2_POS
Q1 --> A1_Q2_NEG
A1_Q2_POS --> A1_R1
A1_Q2_NEG --> A1_R1
A1_R1 --> Q2
Q2 --> Q3
Q3 --> A2_R1
A2_R1 --> Q4
Q4 --> Q5
Q5 --> A3_R1
A3_R1 --> SUMMARY
SUMMARY --> END
