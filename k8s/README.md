# Usage
```
kubectl apply -f k8s-py3-kms.yaml
```
Make sure that the environment you are using supports "loadbalancer"; if not, you can modify the "service" field in the "k8s-py3-kms.yaml" file and use "nodeport".

### window server 2019 key

```
Windows Server 2019 Datacenter  WMDGN-G9PQG-XVVXX-R3X43-63DFG
Windows Server 2019 Standard    N69G4-B89J2-4G8F4-WWYCC-J464C
Windows Server 2019 Essentials  WVDHN-86M7X-466P6-VHXV7-YY726
```

### Client usage

```
slmgr /upk
slmgr /ipk N69G4-B89J2-4G8F4-WWYCC-J464C
slmgr /skms zh.us.to
slmgr /ato
slmgr /xpr
```

### office

```
https://github.com/skymyyang/kms-server
```