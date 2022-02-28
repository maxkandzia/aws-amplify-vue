<template>
  <!--
  Tailwind UI components require Tailwind CSS v1.8 and the @tailwindcss/ui plugin.
  Read the documentation to get started: https://tailwindui.com/documentation
-->

  <div class="max-w-screen-xl mx-auto px-4 py-8 sm:px-6 lg:px-8">
    <div class="bg-white shadow overflow-hidden sm:rounded-lg">
      <div class="px-4 py-5 border-gray-200 sm:px-6">
        <h3 class="text-lg leading-6 font-medium text-gray-900">About Me</h3>

        <p class="mt-1 max-w-2xl text-sm leading-5 text-gray-500">
          <!-- Personal details and application. -->
        </p>
      </div>
      <div>
        <dl>
          <div
            class="bg-gray-50 px-4 py-5 sm:grid sm:grid-cols-3 sm:gap-4 sm:px-6"
          >
            <dt class="text-sm leading-5 font-medium text-gray-500">
              Full name
            </dt>
            <dd
              class="mt-1 text-sm leading-5 text-gray-900 sm:mt-0 sm:col-span-2"
            >
              Maximilian Kandzia
            </dd>
          </div>
          <div
            class="bg-white px-4 py-5 sm:grid sm:grid-cols-3 sm:gap-4 sm:px-6"
          >
            <dt class="text-sm leading-5 font-medium text-gray-500">
              Occupation
            </dt>
            <dd
              class="mt-1 text-sm leading-5 text-gray-900 sm:mt-0 sm:col-span-2"
            >
              Data Engineer / Cloud Engineer
            </dd>
          </div>
          <div
            class="bg-gray-50 px-4 py-5 sm:grid sm:grid-cols-3 sm:gap-4 sm:px-6"
          >
            <dt class="text-sm leading-5 font-medium text-gray-500">
              Email address
            </dt>
            <dd
              class="mt-1 text-sm leading-5 text-gray-900 sm:mt-0 sm:col-span-2"
            >
              maximilian1.kandzia@gmail.com
            </dd>
          </div>

          <div
            class="bg-gray-50 px-4 py-5 sm:grid sm:grid-cols-3 sm:gap-4 sm:px-6"
          >
            <dt class="text-sm leading-5 font-medium text-gray-500">
              Programming languages
            </dt>
            <dd
              class="mt-1 text-sm leading-5 text-gray-900 sm:mt-0 sm:col-span-2"
            >
              Bash, Python, Java, JavaScript, TypeScript, Dart
            </dd>
          </div>
          <div
            class="bg-gray-50 px-4 py-5 sm:grid sm:grid-cols-3 sm:gap-4 sm:px-6"
          >
            <dt class="text-sm leading-5 font-medium text-gray-500">
              Frameworks
            </dt>
            <dd
              class="mt-1 text-sm leading-5 text-gray-900 sm:mt-0 sm:col-span-2"
            >
              Spring Boot, Flutter, Node & Express, Vue.js, Reveal.js, Pandas
            </dd>
          </div>
          <div
            class="bg-gray-50 px-4 py-5 sm:grid sm:grid-cols-3 sm:gap-4 sm:px-6"
          >
            <dt class="text-sm leading-5 font-medium text-gray-500">
              Database
            </dt>
            <dd
              class="mt-1 text-sm leading-5 text-gray-900 sm:mt-0 sm:col-span-2"
            >
              SQL, MySQL, Mongo DB, GraphQL, Cassandra
            </dd>
          </div>
          <div
            class="bg-gray-50 px-4 py-5 sm:grid sm:grid-cols-3 sm:gap-4 sm:px-6"
          >
            <dt class="text-sm leading-5 font-medium text-gray-500">
              Containerization
            </dt>
            <dd
              class="mt-1 text-sm leading-5 text-gray-900 sm:mt-0 sm:col-span-2"
            >
              Docker, Kubernetes, Helm, OpenShift
            </dd>
          </div>
          <div
            class="bg-gray-50 px-4 py-5 sm:grid sm:grid-cols-3 sm:gap-4 sm:px-6"
          >
            <dt class="text-sm leading-5 font-medium text-gray-500">
              Cloud Provider
            </dt>
            <dd
              class="mt-1 text-sm leading-5 text-gray-900 sm:mt-0 sm:col-span-2"
            >
              AWS, Azure
            </dd>
          </div>
          <div
            class="bg-gray-50 px-4 py-5 sm:grid sm:grid-cols-3 sm:gap-4 sm:px-6"
          >
            <dt class="text-sm leading-5 font-medium text-gray-500">
              Infrastructure as Code and automation
            </dt>
            <dd
              class="mt-1 text-sm leading-5 text-gray-900 sm:mt-0 sm:col-span-2"
            >
              Terraform, Ansible
            </dd>
          </div>
          <div
            class="bg-gray-50 px-4 py-5 sm:grid sm:grid-cols-3 sm:gap-4 sm:px-6"
          >
            <dt class="text-sm leading-5 font-medium text-gray-500">
              CI/CD tools
            </dt>
            <dd
              class="mt-1 text-sm leading-5 text-gray-900 sm:mt-0 sm:col-span-2"
            >
              Git, GitLab CI, Github Actions, Harbor, JFrog Artifactory, ArgoCD
            </dd>
          </div>
          <div
            class="bg-gray-50 px-4 py-5 sm:grid sm:grid-cols-3 sm:gap-4 sm:px-6"
          >
            <dt class="text-sm leading-5 font-medium text-gray-500">
              Logging and Monitoring
            </dt>
            <dd
              class="mt-1 text-sm leading-5 text-gray-900 sm:mt-0 sm:col-span-2"
            >
              ELK-Stack, Prometheus, Grafana
            </dd>
          </div>
          
          <div
            class="bg-gray-50 px-4 py-5 sm:grid sm:grid-cols-3 sm:gap-4 sm:px-6"
          >
            <dt class="text-sm leading-5 font-medium text-gray-500">
              Big Data Tools
            </dt>
            <dd
              class="mt-1 text-sm leading-5 text-gray-900 sm:mt-0 sm:col-span-2"
            >
              Kafka, Strimzi, Spark, Databricks
            </dd>
          </div>

          <div
            class="bg-gray-50 px-4 py-5 sm:grid sm:grid-cols-3 sm:gap-4 sm:px-6"
          >
            <dt class="text-sm leading-5 font-medium text-gray-500">UI/UX</dt>
            <dd
              class="mt-1 text-sm leading-5 text-gray-900 sm:mt-0 sm:col-span-2"
            >
              Sketch, Adobe XD
            </dd>
          </div>
          <div
            class="bg-white px-4 py-5 sm:grid sm:grid-cols-3 sm:gap-4 sm:px-6"
          ></div>
        </dl>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AboutMe",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
