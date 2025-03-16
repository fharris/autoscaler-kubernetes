# autoscaler-kubernetes
stuff to explore and test kubernetes autoscaler


#run cpu stresser

1. Deploy cpu stresses
2. Deploy hpa
e.g.
	kubectl autoscale deployment cpu-stressor-deployment --cpu-percent=50 --min=1 --max=50

#reduce cpu stresses

3. Edit deployment resources requests and remove forever flag

 
