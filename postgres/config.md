Host name/address -> postgres-headless.data.svc.cluster.local
maintainance database -> sheba_db
username -> sheba
password -> supersecretpassword
port -> 5432

*********pgadmin login*******
user -> razwanniam1@gmail.com
pass -> razwanniam1@

exec to db ->  kubectl exec -n database -it postgres-0 -- bash
test the connection -> psql -U sheba -d sheba_db -h postgres-headless.database.svc.cluster.local -p 5432
password -> supersecretpassword
