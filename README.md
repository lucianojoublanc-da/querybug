Minimal example for a bug that's present since (at least) SDK 1.12

The problem appears to manifest on line 31, when the key is not found. The error message is:

```shell
Message:
  "Scenario service backend error: BErrorClient (ClientIOError (GRPCIOBadStatusCode StatusUnknown
  (StatusDetails {unStatusDetails = \"\"})))"
```
