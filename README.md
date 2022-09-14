![Logo](https://github.com/PatchMyPCTeam/MEM-Performance-Analzyser/blob/main/patchmypc.png)

# MEM Performance Analyser

This tool run various tests against your WSUS environment, Including WSUS, SQL & IIS and provide feedback based on Microsofts best practices

# Documentation

You can find all docs related to this tool [here](https://docs.patchmypc.com/get-help/mem-performance-analyzer)

## Tests

- Test SUSDB Response Time
- Check that nclLocalizedPropertyID & nclSupercededUpdateID Indexes exist in SUSDB
- Validate that all WSUSContent paths exist & match (Registry, IIS & SUSDB)
- Validate that WSUSContent and UpdateServicesPackages folders have the correct permissions
- Checks the WSUS App Pool in IIS is running
- Check WSUS Administration site for the following
    - Queue legnth matches the microsoft recommendation
    - Idle timeout matches the microsoft recommendation
    - Private memory limit matches the microsoft recommendation
    - Regular time interval matches the microsoft recommendation
    - App pool identity matches the microsoft recommendation
- Checks that the number of superceded & undeclined updates are within recommended limits

More tests will be added as time goes on!

## Feedback & Support

If you have any feedback, please reach out to us at support@patchmypc.com or [open an issue](https://github.com/PatchMyPCTeam/MEM-Performance-Analzyser/issues)