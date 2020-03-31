# Jenkins Helm Chart (customized)

`141` 번의 `serviceType` 을 NodePort로 수정하고 포트번호는`3200`

```yaml
...
# serviceType: ClusterIP
serviceType: NodePort
NodePort: 3200
...
```

PVC는 `pvc-hostpath`, `480`번줄
