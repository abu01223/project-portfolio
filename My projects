import React from "react";
import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import { Mail, Github, Linkedin } from "lucide-react";

export default function Portfolio() {
  return (
    <main className="min-h-screen bg-gray-100 p-4 md:p-12">
      <section className="text-center mb-16">
        <h1 className="text-4xl font-bold mb-2">Abu Talib Mohammed</h1>
        <p className="text-gray-600">MSc Cyber Security | Cloud | DevSecOps | Python | AWS</p>
        <div className="flex justify-center gap-4 mt-4">
          <a href="mailto:Mohdabutalib01@gmail.com"><Mail /></a>
          <a href="https://github.com/abu01223"><Github /></a>
          <a href="https://www.linkedin.com/in/mohammed-abutalib-771453205/"><Linkedin /></a>
        </div>
      </section>

      <section className="mb-12">
        <h2 className="text-2xl font-semibold mb-4">About Me</h2>
        <p className="text-gray-700 max-w-2xl mx-auto">
          Motivated MSc Cyber Security graduate with 3+ years of IT experience in threat detection, network
          security, and system optimization. Hands-on with Wireshark, Splunk, Kali Linux, Python, and AWS. Passionate
          about solving real-world security problems through DevSecOps and ML integration.
        </p>
      </section>

      <section className="mb-12">
        <h2 className="text-2xl font-semibold mb-4">Projects</h2>
        <div className="grid grid-cols-1 md:grid-cols-2 gap-6">
          <Card>
            <CardContent className="p-4">
              <h3 className="text-xl font-bold">Resume Evaluation System</h3>
              <p className="text-gray-600 mb-2">
                Built with AI and Text Mining to streamline recruitment processes.
              </p>
              <Button asChild>
                <a href="https://github.com/abu01223/resume-evaluation-system" target="_blank">View on GitHub</a>
              </Button>
            </CardContent>
          </Card>

          <Card>
            <CardContent className="p-4">
              <h3 className="text-xl font-bold">Human Behavior Analysis via Twitter</h3>
              <p className="text-gray-600 mb-2">
                ML-based sentiment analysis system using tweets to extract patterns.
              </p>
              <Button asChild>
                <a href="https://github.com/abu01223/twitter-behavior-analysis" target="_blank">View on GitHub</a>
              </Button>
            </CardContent>
          </Card>

          <Card>
            <CardContent className="p-4">
              <h3 className="text-xl font-bold">DevSecOps + ML Threat Detection</h3>
              <p className="text-gray-600 mb-2">
                Dissertation project integrating DevSecOps with machine learning for real-time cyber-attack detection in cloud-native environments.
              </p>
              <Button asChild>
                <a href="https://github.com/abu01223/devsecops-ml-detection" target="_blank">View on GitHub</a>
              </Button>
            </CardContent>
          </Card>
        </div>
      </section>

      <section className="text-center">
        <h2 className="text-2xl font-semibold mb-4">Contact Me</h2>
        <p className="text-gray-700">Email: Mohdabutalib01@gmail.com</p>
        <p className="text-gray-700">Location: London, UK</p>
      </section>
    </main>
  );
}
