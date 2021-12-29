query {
  messages{
    id
    user
    content
  }
}

mutation postFeed{
	postMessage(user: "Pam",content: "Hi"){
    id
    user
    content
  }
}