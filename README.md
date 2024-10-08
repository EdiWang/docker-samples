# Docker Samples

Sample Dockerfile for build apps

## Examples

Combination | Example Directory | Build | Run
--|--|--|--
Angular + Nginx | `./angular-nginx` | `docker build . -t example-angular-nginx` | `docker run -d -p 80:80 example-angular-nginx`
React + Nginx | `./react-nginx` | `docker build . -t example-react-nginx` | `docker run -d -p 80:80 example-react-nginx`
Pure HTML + Nginx | `./static-html-nginx` | `docker build . -t example-static-html-nginx` | `docker run -d -p 80:80 example-static-html-nginx`
Pure HTML + SWS | `./static-html-sws` | `docker build . -t example-static-html-sws` | `docker run -d -p 8080:8080 example-static-html-sws`

## 免责申明

此项目(docker-samples)及其配套组件均为免费开源的产品，仅用于学习交流，并且不直接向中国提供服务，中国访客请于下载后立即删除。

任何中国境内的组织及个人不得使用此项目(docker-samples)及其配套组件构建任何形式的面向中国境内访客的网站或服务。

不可用于任何违反中华人民共和国(含台湾省)或使用者所在地区法律法规的用途。

因为作者即本人仅完成代码的开发和开源活动(开源即任何人都可以下载使用)，从未参与访客的任何运营和盈利活动。

且不知晓访客后续将程序源代码用于何种用途，故访客使用过程中所带来的任何法律责任即由访客自己承担。

[《开源软件有漏洞，作者需要负责吗？是的！》](https://go.edi.wang/aka/os251)