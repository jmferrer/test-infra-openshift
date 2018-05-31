# test-infra-openshift

En este repo van los playbooks/scripts o lo que sea necesario para dárselo al cliente y que compruebe que la infraestructura funcione antes de ir allí.

Hay que comprobar al menos el balanceo al master y a los nodos y la resolución de nombres.

Se abrirá un ticket para cada funcionalidad y se agregarán a medida que se vayan necesitando más.

Ejecución:
```
ansible-playbook -i hosts ansible/main.yml
```
