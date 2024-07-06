# **Oleg Makarov**

## **Front-end Developer**
---
### Contact information:

**Phone:** +995 557 66 44 69

**E-mail:** olegmakarovach.job@gmail.com

**Telegram:** @olegacat

[LinkedIn](https://www.linkedin.com/in/oleg-makarov-6a0789266/)

[Github](https://github.com/olegacaten)



## About me

I am dedicated and passionate web developer, who wants to create dynamic, useful apps that will provide, best experience and will help for people to reach their goals. I continuously improve my skills and study every day to make high-quality solutions. 

## Technical Skills

**Front-End**
- HTML, CSS, SCSS
- React, React Native
- JavaScript, TypeScript
- Redux
- MUI, Boostrap

**Back-End**
- PHP, SoketIO, GraphQL
- MySQL, MongoDB, Supabase

**Tools and Methologies**
- Figma, MVC, PS, AI, Postman, Git

**Languages**
- English C1
- Russian Native

## Code examples 

`Talk bridges code:

const http = require('http');
const socketIO = require('socket.io');
const server = http.createServer();
const io = socketIO(server);

io.on('connection', socket => {
    let room = '';

    socket.on('join', chatId => {
        room = chatId;
        console.log(chatId);
        socket.join(chatId);
    });

    socket.on('send_message', message => {
      io.to(room).emit('get_message', message);
    });

    // Обработчик отключения клиента
    socket.on('disconnect', () => {
        console.log('Client disconnected');
    });
});

const port = process.env.PORT || 8082;
    server.listen(port, () => {
    console.log(`Server listening on port ${port}`);
});

const os = require('os');
const { networkInterfaces } = os;

// Get a list of network interfaces
const interfaces = networkInterfaces();

// Filter for IPv4 addresses
const ipv4Addresses = {};

for (const name of Object.keys(interfaces)) {
  for (const iface of interfaces[name]) {
    if (iface.family === 'IPv4' && !iface.internal) {
      ipv4Addresses[name] = iface.address;
    }
  }
}

console.log(ipv4Addresses);
`
# Work Experience 

### Student Website
- **Description:** Build Feed page. 
- **Stacks:** React, SCSS, JS, Feature-Sliced Design

### Ama Group, Website for advertisement company
- **Description:** Build and maintained the website for a client, messages send directly to telegram bot for the client. 
- **Stacks:** JS, jQuery, PHP, CSS, HTML

### Chat Application
- **Description:** Simple chat, with privat chats and group chats. 
- **Stacks:** React, CSS, Redux, SoketIO, PHP
