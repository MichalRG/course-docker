COMMANDS IN SECTION:
68 docker container prune
69 docker run --rm -d --name mongodb -p 27017:27017 mongo
70 docker ps
71 cd .\backend\
 72 npm i
73 node .\app.js
74 docker ps
75 docker logs mongodb
76 docker image prune -a
77 docker build -t goals-node .
78 docker build -t goals-node .
79 docker run --name goals-backend --rm -d goals-node
80 docker ps
81 docker logs goals-backend
82 docker stop goals-backend
83 docker run --name goals-backend --rm -d -p 80:80 goals-node
84 cd ..
85 cd .\frontend\
 86 docker build -t goals-react .
87 docker run --name goals-frontend --rm -p 3000:3000 --it goals-react
88 docker run --name goals-frontend --rm -p 3000:3000 -it goals-react
89 docker ps
90 docker stop goals-backend
91 docker stop mongodb
98 docker ps
99 docker ps -a
100 docker images
101 docker network create goals-net
102 docker run --name mongodb --rm -d --network goals-net mongo
103 docker ps
104 cd ..
105 cd .\backend\
 106 docker build -t goals-node .
107 docker run -d --rm --network goals-net goals-node
108 docker ps
109 docker stop quirky*shaw
110 docker run --name goals-backend -d --rm --network goals-net goals-node
111 docker ps
112 cd ..
113 cd .\frontend\
 114 docker build -t goals-react .
115 docker run --name goals-frontend --rm -d --it --network goals-net -p 3000:3000 goals-react
116 docker run --name goals-frontend --rm -d -it --network goals-net -p 3000:3000 goals-react
117 docker ps
118 docker logs goals-react
119 docker logs goals-frontend
120 docker stop goals-react
121 docker stop goals-frontend
122 docker build -t goals-react .
123 docker run --name goals-frontend --rm -d -it -p 3000:3000 goals-react
124 cd ..
125 cd .\backend\
 126 docker ps
127 docker stop golas-backend
128 docker stop goals-backend
129 docker run --rm -d --name goals-backend -p 80:80 --network goals-net goals-node
130 docker ps
131 docker stop mongodb
132 cd ..
133 docker run --name mongodb --rm -d --network goals-net -v data:/data/db mongo
134 docker stop mongodb
135 docker run --name mongodb --rm -d --network goals-net -v data:/data/db mongo
136 docker ps
137 docker stop mongodb
138 docker run --name mongodb --rm -d --network goals-net -v data:/data/db -e MONGO_INITDB_ROOT_USERNAME=michal -e MONGO*...
139 cd .\backend\
 140 docker stop goals-backend
141 docker build -t golas-node .
142 docker run -d --rm --name goals-backend -p 80:80 --network goals-net goals-node
143 docker ps -a
144 docker ps -a
145 docker logs goals-backend
146 docker logs goals-backend
147 docker stop goals-backend
148 docker run -d --rm --name goals-backend -p 80:80 --network goals-net goals-node
149 docker ps -a
150 docker ps -a
151 docker logs goals-backend
152 docker ps
153 docker stop mongodb
154 docker volume ls
155 docker volume rm data
156 docker volume ls
157 history
158 docker run --network goals-net -d --rm --name mongodb -v data:/data/db -e MONGO*INITDB_ROOT_USERNAME=michal -e MONGO*...
159 docker ps
160 docker logs goals-backend
161 docker stop goals-backend
162 docker buld -t goals-node .
163 docker build -t goals-node .
164 docker run --rm -d -p 80:80 --name docker-backend --network goals-net goals-node
165 docker ps -a
166 docker logs mongodb
167 docker logs goals-backend
168 docker ps -a
169 docker ps
170 docker logs docker-backend
171 history
172 docker stop docker-backend
173 docker build -t goals-node .
174 docker run --rm -d -p 80:80 --name goals-backend --network goals-net -v D:\Docker\081024-multi-01-starting-setup\mult...
175 docker ps
176 docker logs goals-backend
177 docker logs goals-backend
178 docker stop goals-backend
179 docker build -t goals-node .
180 docker run --rm -d -p 80:80 --name goals-backend --network goals-net -v D:\Docker\081024-multi-01-starting-setup\mult...
181 docker ps
182 docker logs goals-backend
183 docker logs goals-backend
184 docker logs goals-backend
185 docer stop goals-backend
186 docler stop goals-backend
187 docker stop goals-backend
188 docker run --rm -d -p 80:80 --name goals-backend --network goals-net -v D:\Docker\081024-multi-01-starting-setup\mult...
189 docker logs goals-backend
190 docker stop goals-backend
191 docker build -t goals-node .
192 docker run --rm -d -p 80:80 --name goals-backend --network goals-net -v D:\Docker\081024-multi-01-starting-setup\mult...
193 cd ..
194 cd .\frontend\
 195 docker stop goals-frontend
196 docker run -v D:\Docker\081024-multi-01-starting-setup\multi-01-starting-setup\frontend\src:/app/src --rm -d -it --na...
197 docker ps
198 docker logs goals-frontend
199 docker logs goals-frontend
200 docker ps
201 docker sto goals-frontend
202 docker stop goals-frontend
203 docker run -v D:\Docker\081024-multi-01-starting-setup\multi-01-starting-setup\frontend\src:/app/src --rm -d -it --na...
204 docker ps
205 docker logs goals-frontend
