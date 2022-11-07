```bash
yum install -y bash-completion
echo 'source <(kubectl completion bash)' >> /root/.bashrc
echo 'source <(crictl completion bash)' >> /root/.bashrc
```