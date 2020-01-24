# TODO
- [x] do not mount token by default, add serviceaccount
- [x] implement pod security policy
- [x] configure external configmap, reload deployment on config update
- [x] add ability to store buffers in PBC
- [x] setup default soft antiaffinity
- [x] add ability to specify ports/names and service types
- [x] make custom pod distruption budget
- [x] enable custom rolling update strategy
- [ ] create prometheus servicemonitor (for prometheus sink)
- [ ] add ability to inject custom sidecar (for integration with datadog agent)
- [ ] add tests to check if chart installed/updated succesful
- [ ] setup readiness/liveness check