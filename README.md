# LuckData-mobile-tiktok-online-api
LuckData mobile tiktok online api You don’t need to use complex code. Use our mobile tiktok online api to meet your business needs. All operations are as simple as copy-paste, even for non-technical users.

# How to Use
Step 1: Click “Get Started”
Step 2: Purchase a plan and complete the payment
Step 3: Choose your preferred run mode
Step 4: Click "Test Endpoint"

# Code Snippets

Code examples include python, Java, go, etc.

## python

<pre>import requests

headers = {
    'X-Luckdata-Api-Key': 'your key'
}

json_data={}

response = requests.get(
    'https://luckdata.io/api/mobile-tiktok-api/get_239f?count=10&offset=0&keyword=nike',
    headers=headers,
    
)
print(response.json())</pre>

## java

<pre>import java.io.IOException;
import java.net.URI;
import java.net.http.HttpClient;
import java.net.http.HttpRequest;
import java.net.http.HttpResponse;

HttpClient client = HttpClient.newHttpClient();

HttpRequest request = HttpRequest.newBuilder()
    .uri(URI.create("https://luckdata.io/api/mobile-tiktok-api/get_239f?count=10&offset=0&keyword=nike"))
    .GET()
    
    .setHeader("X-Luckdata-Api-Key", "your key")
    .build();

HttpResponse<String> response = client.send(request, HttpResponse.BodyHandlers.ofString());</pre>

## go

<pre>package main

import (
  "fmt"
  "io"
  "log"
  "net/http"
  "strings"
)

func main() {
  client := &http.Client{}
  var data = nil
  req, err := http.NewRequest("GET", "https://luckdata.io/api/mobile-tiktok-api/get_239f?count=10&offset=0&keyword=nike", data)
  if err != nil {
    log.Fatal(err)
  }
  
  req.Header.Set("X-Luckdata-Api-Key", "your key")
  resp, err := client.Do(req)
  if err != nil {
    log.Fatal(err)
  }
  defer resp.Body.Close()
  bodyText, err := io.ReadAll(resp.Body)
  if err != nil {
    log.Fatal(err)
  }
  fmt.Printf("%s\n", bodyText)
}</pre>

## shell

<pre>curl -X GET "https://luckdata.io/api/mobile-tiktok-api/get_239f?count=10&offset=0&keyword=nike"  -H "X-Luckdata-Api-Key":"your key" </pre>

# MORE

For more information about LuckData mobile tiktok online api, please click:<a href="https://luckdata.io/marketplace/detail/mobile-tiktok-api">LuckData mobile tiktok online api</a>
