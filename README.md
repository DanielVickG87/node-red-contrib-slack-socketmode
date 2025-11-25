# node-red-contrib-slack-rtm

A Node-RED node that enables real-time bi-directional communication with Slack using the **Slack RTM API (Socket Mode)**.  

This node allows you to:
- Receive messages from any Slack channel, DM or app mention.
- Send messages from Node-RED to Slack using the same authenticated connection.
- Run a persistent background Slack RTM client that automatically reconnects.
- Avoid the need for external tunnels (like ngrok), as Slack Socket Mode requires **no public URL**.

This package is useful when building:
- ChatOps automations
- Monitoring or alerting pipelines
- IoT → Slack integrations
- Slack assistants connected to industrial SCADA/PLC systems
- Internal automation bots without requiring slash commands or HTTP endpoints

---

# 🔧 Installation

### **Using npm**
```bash
cd ~/.node-red
npm install node-red-contrib-slack-rtm
