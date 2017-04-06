node {
  properties([parameters([string(defaultValue: 'default', description: '', name: 'namespace'), string(name:'filename')])])
  checkout scm
  sh("kubectl apply -n ${params.namespace} -f ${params.namespace}/${params.filaname}")
}
