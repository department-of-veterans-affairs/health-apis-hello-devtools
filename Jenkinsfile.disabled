standardMavenPipeline {
  healthApisMavenImage='vasdvp/health-apis-maven:3.6-jdk-12'
  credentials = [ string( credentialsId: 'SLACK_WEBHOOK_FOR_METRICS', variable: 'SLACK_WEBHOOK_FOR_METRICS' ) ]
  slackChannels = ['health_apis_jenkins']
  slackDestinations = [ 'shanktovoid@${env.SLACK_WEBHOOK_FOR_METRICS}' ]
}
