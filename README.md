# llg-go
A last letter game benchmark implemented in Go

## How to run
Clone repository recursively:

```bash
git clone --recursive https://github.com/LLGAssessment/llg-go.git
```

Build an executable:

```bash
cd llg-go
go build lastlettergame.go
```

then run a benchmark

```bash
time ./lastlettergame < llg-dataset/70pokemons.txt
```
