#!/usr/bin/env groovy
/*
 * ao-oss-parent - Parent POM for all AO open-source software projects.
 * Copyright (C) 2021, 2022, 2023, 2024, 2025, 2026  AO Industries, Inc.
 *     support@aoindustries.com
 *     7262 Bull Pen Cir
 *     Mobile, AL 36695
 *
 * This file is part of ao-oss-parent.
 *
 * ao-oss-parent is free software: you can redistribute it and/or modify
 * it under the terms of the GNU Lesser General Public License as published by
 * the Free Software Foundation, either version 3 of the License, or
 * (at your option) any later version.
 *
 * ao-oss-parent is distributed in the hope that it will be useful,
 * but WITHOUT ANY WARRANTY; without even the implied warranty of
 * MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
 * GNU Lesser General Public License for more details.
 *
 * You should have received a copy of the GNU Lesser General Public License
 * along with ao-oss-parent.  If not, see <https://www.gnu.org/licenses/>.
 */

// Parent, Extensions, Plugins, Direct and BOM Dependencies
binding.setVariable('upstreamProjects', [
  // Extensions
  // No Jenkins: <groupId>org.apache.maven.wagon</groupId><artifactId>wagon-ssh-external</artifactId>

  // Plugins
  // No Jenkins: <groupId>org.simplify4u.plugins</groupId><artifactId>pgpverify-maven-plugin</artifactId>
  // No Jenkins: <groupId>org.apache.axis2</groupId><artifactId>axis2-aar-maven-plugin</artifactId>
  // No Jenkins: <groupId>org.codehaus.mojo</groupId><artifactId>exec-maven-plugin</artifactId>
  // No Jenkins: <groupId>io.github.git-commit-id</groupId><artifactId>git-commit-id-maven-plugin</artifactId>
  // No Jenkins: <groupId>org.apache.maven.plugins</groupId><artifactId>maven-compiler-plugin</artifactId>
  // No Jenkins: <groupId>org.apache.maven.plugins</groupId><artifactId>maven-enforcer-plugin</artifactId>
  // No Jenkins: <groupId>org.apache.maven.plugins</groupId><artifactId>maven-resources-plugin</artifactId>
  // No Jenkins: <groupId>org.jacoco</groupId><artifactId>jacoco-maven-plugin</artifactId>
  // No Jenkins: <groupId>org.apache.maven.plugins</groupId><artifactId>maven-surefire-plugin</artifactId>
  // No Jenkins: <groupId>org.apache.maven.plugins</groupId><artifactId>maven-dependency-plugin</artifactId>
  // No Jenkins: <groupId>org.apache.felix</groupId><artifactId>maven-bundle-plugin</artifactId>
  // No Jenkins: <groupId>org.codehaus.mojo</groupId><artifactId>build-helper-maven-plugin</artifactId>
  // No Jenkins: <groupId>io.reformanda.semper</groupId><artifactId>dependencyversion-maven-plugin</artifactId>
  // No Jenkins: <groupId>org.sonatype.ossindex.maven</groupId><artifactId>ossindex-maven-plugin</artifactId>
  // No Jenkins: <groupId>org.apache.maven.plugins</groupId><artifactId>maven-release-plugin</artifactId>
  // No Jenkins: <groupId>org.codehaus.mojo</groupId><artifactId>versions-maven-plugin</artifactId>
  // No Jenkins: <groupId>org.apache.maven.plugins</groupId><artifactId>maven-gpg-plugin</artifactId>
  // No Jenkins: <groupId>org.apache.maven.plugins</groupId><artifactId>maven-clean-plugin</artifactId>
  // No Jenkins: <groupId>org.apache.maven.plugins</groupId><artifactId>maven-deploy-plugin</artifactId>
  // No Jenkins: <groupId>org.apache.maven.plugins</groupId><artifactId>maven-install-plugin</artifactId>
  // No Jenkins: <groupId>org.apache.maven.plugins</groupId><artifactId>maven-jar-plugin</artifactId>
  // No Jenkins: <groupId>org.apache.maven.plugins</groupId><artifactId>maven-remote-resources-plugin</artifactId>
  // No Jenkins: <groupId>org.apache.maven.plugins</groupId><artifactId>maven-war-plugin</artifactId>
  // No Jenkins: <groupId>org.apache.maven.plugins</groupId><artifactId>maven-source-plugin</artifactId>
  // No Jenkins: <groupId>org.apache.maven.plugins</groupId><artifactId>maven-javadoc-plugin</artifactId>
  // No Jenkins: <groupId>org.apache.maven.plugins</groupId><artifactId>maven-antrun-plugin</artifactId>
  // No Jenkins: <groupId>org.apache.maven.plugins</groupId><artifactId>maven-checkstyle-plugin</artifactId>
  // No Jenkins: <groupId>com.github.spotbugs</groupId><artifactId>spotbugs-maven-plugin</artifactId>
  // No Jenkins: TODO: Try findsecbugs-plugin: <groupId>com.h3xstream.findsecbugs</groupId><artifactId>findsecbugs-plugin</artifactId>
  // No Jenkins: <groupId>org.apache.maven.plugins</groupId><artifactId>maven-site-plugin</artifactId>
  // No Jenkins: <groupId>org.sonarsource.scanner.maven</groupId><artifactId>sonar-maven-plugin</artifactId>
  // No Jenkins: <groupId>org.apache.maven.plugins</groupId><artifactId>maven-shade-plugin</artifactId>
  // No Jenkins: <groupId>org.apache.maven.plugins</groupId><artifactId>maven-jarsigner-plugin</artifactId>
  // No Jenkins: <groupId>org.apache.tomcat.maven</groupId><artifactId>tomcat7-maven-plugin</artifactId>
  // No Jenkins: <groupId>org.codehaus.mojo</groupId><artifactId>properties-maven-plugin</artifactId>
  // No Jenkins: <groupId>org.eclipse.jetty</groupId><artifactId>jetty-maven-plugin</artifactId>
  // No Jenkins: <groupId>org.apache.maven.plugins</groupId><artifactId>maven-project-info-reports-plugin</artifactId>
  // No Jenkins: <groupId>org.sonatype.plugins</groupId><artifactId>nexus-staging-maven-plugin</artifactId>

  // Plugin Dependencies
  // No Jenkins: <groupId>org.simplify4u</groupId><artifactId>pgp-keys-map</artifactId>
  // Avoid cyclic dependency: 'pgp-keys-map', // <groupId>com.aoapps</groupId><artifactId>pgp-keys-map</artifactId>
  // No Jenkins: <groupId>org.codehaus.mojo</groupId><artifactId>extra-enforcer-rules</artifactId>
  // No Jenkins: <groupId>org.ow2.asm</groupId><artifactId>asm</artifactId>
  // No Jenkins: <groupId>com.puppycrawl.tools</groupId><artifactId>checkstyle</artifactId>
  // No Jenkins: <groupId>com.github.spotbugs</groupId><artifactId>spotbugs</artifactId>
  // Avoid cyclic dependency: 'javadoc-offline', // <groupId>com.aoapps</groupId><artifactId>ao-javadoc-offline</artifactId>
  // Avoid cyclic dependency: 'javadoc-resources', // <groupId>com.aoapps</groupId><artifactId>ao-javadoc-resources</artifactId>
  // Avoid cyclic dependency: 'ant-tasks', // <groupId>com.aoapps</groupId><artifactId>ao-ant-tasks</artifactId>
  // No Jenkins: <groupId>org.apache.commons</groupId><artifactId>commons-compress</artifactId>
  // No Jenkins: <groupId>commons-io</groupId><artifactId>commons-io</artifactId>
  // No Jenkins: <groupId>org.apache.commons</groupId><artifactId>commons-lang3</artifactId>
  // No Jenkins: <groupId>org.apache.commons</groupId><artifactId>commons-text</artifactId>
  // Avoid cyclic dependency: 'checkstyle-config', // <groupId>com.aoapps</groupId><artifactId>ao-checkstyle-config</artifactId>
])

/******************************************************************************************
 *                                                                                        *
 * Everything below this line is identical for all projects, except the copied matrix     *
 * axes and any "Begin .*custom" / "End .*custom" blocks (see filter_custom script).      *
 *                                                                                        *
 *****************************************************************************************/

// Load ao-jenkins-shared-library
// TODO: Put @Library on import once we have our first library class
// TODO: Replace master with a specific tag version number once working
@Library('ao@master') _
ao.setVariables(binding, currentBuild, scm, params)

pipeline {
  agent any
  options {
    ansiColor('xterm')
    disableConcurrentBuilds(abortPrevious: true)
    quietPeriod(quietPeriod)
    skipDefaultCheckout()
    timeout(time: PIPELINE_TIMEOUT, unit: TIMEOUT_UNIT)
    // Only allowed to copy build artifacts from self
    // See https://plugins.jenkins.io/copyartifact/
    copyArtifactPermission("/${JOB_NAME}")
  }
  parameters {
    string(
      name: 'BuildPriority',
      defaultValue: "$buildPriority",
      description: BuildPriority_description
    )
    booleanParam(
      name: 'abortOnUnreadyDependency',
      defaultValue: true,
      description: abortOnUnreadyDependency_description
    )
    booleanParam(
      name: 'requireLastBuild',
      defaultValue: true,
      description: requireLastBuild_description
    )
    booleanParam(
      name: 'mavenDebug',
      defaultValue: false,
      description: mavenDebug_description
    )
  }
  triggers {
    upstream(
      threshold: hudson.model.Result.SUCCESS,
      upstreamProjects: "${prunedUpstreamProjects.join(', ')}"
    )
  }
  stages {
    stage('Setup') {
      steps {
        script {
          // Additional setup that cannot be done in options inside declarative pipeline
          ao.setupBuildDiscarder()
        }
      }
    }
    stage('Check Ready') {
      when {
        expression {
          return (params.abortOnUnreadyDependency == null) ? true : params.abortOnUnreadyDependency
        }
      }
      steps {
        script {
          ao.checkReadySteps()
        }
      }
    }
    stage('Workaround Git #27287') {
      when {
        expression {
          ao.continueCurrentBuild() && projectDir != '.' && fileExists('.gitmodules')
        }
      }
      steps {
        script {
          ao.workaroundGit27287Steps(scmUrl, scmBranch, scmBrowser, sparseCheckoutPaths, disableSubmodules)
        }
      }
    }
    stage('Checkout SCM') {
      when {
        expression {
          ao.continueCurrentBuild()
        }
      }
      steps {
        script {
          ao.checkoutScmSteps(projectDir, niceCmd, scmUrl, scmBranch, scmBrowser, sparseCheckoutPaths, disableSubmodules)
        }
      }
    }
    stage('Builds') {
      matrix {
        when {
          expression {
            ao.continueCurrentBuild()
          }
        }
        axes {
          axis {
            name 'jdk'
            values '11', '17', '21' // buildJdks
          }
        }
        stages {
          stage('Build') {
            steps {
              script {
                ao.buildSteps(projectDir, niceCmd, maven, deployJdk, mavenOpts, mvnCommon, jdk, buildPhases, testWhenExpression, testJdks)
              }
            }
          }
        }
      }
    }
    stage('Tests') {
      matrix {
        when {
          expression {
            ao.continueCurrentBuild() && testWhenExpression.call()
          }
        }
        axes {
          axis {
            name 'jdk'
            values '11', '17', '21' // buildJdks
          }
          axis {
            name 'testJdk'
            values '11', '17', '21' // testJdks
          }
        }
        stages {
          stage('Test') {
            steps {
              script {
                ao.testSteps(projectDir, niceCmd, deployJdk, maven, mavenOpts, mvnCommon, jdk, testJdk)
              }
            }
          }
        }
      }
    }
    stage('Deploy') {
      when {
        expression {
          ao.continueCurrentBuild()
        }
      }
      steps {
        script {
          ao.deploySteps(projectDir, niceCmd, deployJdk, maven, mavenOpts, mvnCommon)
        }
      }
    }
    stage('SonarQube analysis') {
      when {
        expression {
          ao.continueCurrentBuild() && sonarqubeWhenExpression.call()
        }
      }
      steps {
        script {
          ao.sonarQubeAnalysisSteps(projectDir, niceCmd, deployJdk, maven, mavenOpts, mvnCommon)
        }
      }
    }
    stage('Quality Gate') {
      when {
        expression {
          ao.continueCurrentBuild() && sonarqubeWhenExpression.call()
        }
      }
      steps {
        script {
          ao.qualityGateSteps()
        }
      }
    }
    stage('Analysis') {
      when {
        expression {
          ao.continueCurrentBuild()
        }
      }
      steps {
        script {
          ao.analysisSteps()
        }
      }
    }
  }
  post {
    failure {
      script {
        ao.postFailure(failureEmailTo)
      }
    }
    // Begin custom
    always {
      // Rename pom.xml so as to not have old left-over versions of parents picked-up by other projects.
      // Trying to use <relativePath /> on all projects broke our developer reactor builds, so this is our workaround.
      script {
        if (fileExists('pom.xml')) {
          sh "${niceCmd}mv -T -f pom.xml pom-do-not-use-me-as-parent.xml"
        }
      }
    }
    // End custom
  }
}
