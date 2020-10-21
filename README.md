# Set up a postgresql based on Azure File running with Statefulset

```
kubectl create secret generic foo-db-creds --from-literal username=test --from-literal password="Abc@123"
kubectl create -f https://raw.githubusercontent.com/alftio/aksPV/main/postgresqlstatefulset.yaml 

```
