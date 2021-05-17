To run, use the following command:

```
Microsoft.Health.Fhir.Anonymizer.Benchmarks\\> dotnet run -c Release -- --filter *Processors*
```

## Prerequisites for Plots

1. Perl
   - `winget install --id="ActiveState.ActivePerl" --exact`

2. R
   - `choco install R`
   - add rscript to your `PATH` (C:\Program Files\R\R-4.0.5\bin)
   - add r folder to `R_HOME` (C:\Program Files\R\R-4.0.5)

3. R 
   - Run `R` from command line
   - `R> install.packages("ggplot2")`

## Troiubleshooting plots

If plots are not generated, manually execute `Rscript BuildPlots.R` from the BenchmarkDotNet\results folder.