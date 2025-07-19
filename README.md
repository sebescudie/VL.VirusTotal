# VL.VirusTotal

A little node set to make requests to the [VirusTotal V3 REST API](https://docs.virustotal.com/docs/api-overview).

> [!NOTE]  
> Currently, this library will only support a (very) limited subset of the VirusTotal V3 API, as I am wrapping it for a personal project.
> There are no plans for a complete implementation, but feel free to reach out if you need a more comprehensive version.

## Supported features

### File Report

For a file-hash, the library will return:

- Reputation score
- Last analysis results: security industry scan results for the hash you provided
- Last analysis stats: how many vendors flagged your sample as malicious/harmless, etc
- Suggested Threat Label
- Submission Stats: when was your sample first/last submitted, how many times, etc