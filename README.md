# Processador MIPS de Ciclo Único em Verilog

Este projeto implementa um **processador MIPS de ciclo único** em **Verilog**, seguindo a arquitetura apresentada no livro *Computer Organization and Design* (David A. Patterson & John L. Hennessy).  
O processador foi desenvolvido de forma **modularizada** e testado via simulação com **Icarus Verilog** e **GTKWave**.

---

## Funcionalidades

- Implementação da arquitetura MIPS de ciclo único.  
- Suporte às instruções:  
  - **R-type:** `add`, `sub`, `and`, `or`, `slt`  
  - **I-type:** `addi`, `lw`, `sw`, `beq`
