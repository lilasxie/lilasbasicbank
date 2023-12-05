# lilasbasicbank.aleo

## Build Guide

To compile this Aleo program, run:
```bash
snarkvm build
```

To execute this Aleo program, run:
```bash
snarkvm run hello
```

## Commands

### issue
```shell
leo run issue aleo185hj0yknz535yx83pntc9wzpx5xcf5u7mjplyrygs8m7efh0curqke78z0 1000000u64
```
record the outputs

### deposit
```shell
leo run deposit "{owner: aleo185hj0yknz535yx83pntc9wzpx5xcf5u7mjplyrygs8m7efh0curqke78z0.private,amount: 1000000u64.private,_nonce: 7021184866183391885862196513712023493211074630152864558654742306589390649218group.public}" 500000u64
```
record the outputs

### estimate
```shell
leo run estimate 500000u64 300u64 80u64
```

### withdraw
```shell
leo run withdraw aleo185hj0yknz535yx83pntc9wzpx5xcf5u7mjplyrygs8m7efh0curqke78z0 500000u64 300u64 80u64
```