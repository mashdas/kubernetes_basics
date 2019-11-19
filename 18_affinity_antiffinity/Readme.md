* Node Affinity is similar to the nodeSelector

* Pod affinity/anti-affinity allows you to create rules how pods sjould be scheduled taking into account other running pods

* Affinity/anti-affinity mechanism is only relevant during scheduling,once the pod is ruuning,it'll need to be recreated(the pods) to apply the rules again