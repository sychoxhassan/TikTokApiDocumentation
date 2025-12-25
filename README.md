<div align="center">

<!-- Animated Banner -->
<img src="https://raw.githubusercontent.com/sychoxhassan/Assets/main/assets/logo.png" width="160" height="160" alt="TikSave API">

<br>

# 🎵 TikSave API

<h3>
  <p align="center">
  <img 
    src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=FF0050&center=true&vCenter=true&width=340&lines=Download+TikTok+Videos;No+Watermark;Free+Unlimited+API;No+API+Key+Required;Fast+Response"
    alt="Typing SVG"
  />
  </p>

<br>

<!-- Animated Stats -->
<p>
  <a href="https://api-social-sooty.vercel.app/" target="_blank">
  <img src="https://img.shields.io/badge/🚀_API_Status-ONLINE-00FF00?style=for-the-badge&labelColor=0D1117" alt="Status">
  </a>
  <img src="https://img.shields.io/badge/⚡_Response-~150ms-blueviolet?style=for-the-badge&labelColor=0D1117" alt="Speed">
  <img src="https://img.shields.io/badge/🔓_Auth-NOT_REQUIRED-FF0050?style=for-the-badge&labelColor=0D1117" alt="Auth">
</p>

<p>
  <img src="https://img.shields.io/badge/Uptime-99.99%25-success?style=flat-square&logo=checkmarx&logoColor=white">
  <img src="https://img.shields.io/badge/Rate_Limit-∞_Unlimited-gold?style=flat-square&logo=infinity&logoColor=white">
  <img src="https://img.shields.io/badge/Languages-18+-00F2EA?style=flat-square&logo=code&logoColor=white">
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square&logo=opensourceinitiative&logoColor=white">
</p>

<br>

<!-- Fun Navigation -->
<p>
  <a href="#-quick-start"><img src="https://img.shields.io/badge/🚀-Quick_Start-FF0050?style=for-the-badge" alt="Quick Start"></a>
  <a href="#-api-documentation"><img src="https://img.shields.io/badge/📖-API_Docs-00F2EA?style=for-the-badge" alt="API Docs"></a>
  <a href="#-code-examples"><img src="https://img.shields.io/badge/💻-Examples-7C3AED?style=for-the-badge" alt="Examples"></a>
  <a href="#-meet-the-team"><img src="https://img.shields.io/badge/👥-Team-FFD700?style=for-the-badge" alt="Team"></a>
</p>

<br>

---

<br>

<!-- Fun Intro Section -->
<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="700">

<br><br>

### 🤔 What is TikSave API?

**TikSave API** is a **FREE** and **UNLIMITED** API that lets you download TikTok videos **without watermark** in **HD quality**! 

No signup. No API keys. No rate limits. Just pure awesomeness! 🎉

<br>

</div>

<div align="center">

## 🚀 Quick Start

### Get started in literally **10 seconds**! ⏱️

</div>

<br>

### 📡 Base URL
```
https://api-social-sooty.vercel.app
```

### 🔗 Endpoint
```http
GET /api/tiktok?url={TIKTOK_VIDEO_URL}
```

### ⚡ Try It Now!
```bash
curl "https://api-social-sooty.vercel.app/api/tiktok?url=https://vm.tiktok.com/ZNRNw695H" | jq
```

<br>

<div align="center">

<a href="https://api-social-sooty.vercel.app/api/tiktok?url=https://vm.tiktok.com/ZNRNw695H">
<img src="https://img.shields.io/badge/🧪_CLICK_TO_TEST_LIVE_API-FF0050?style=for-the-badge&labelColor=0D1117" alt="Try Live">
</a>

<br><br>

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="500">

</div>

<br>

---

<br>

<div align="center">

## 📖 API Documentation

</div>

<br>

### 📥 Request Parameters

| Parameter | Type | Required | Description |
|:--|:--|:--:|:--|
| `url` | `string` | ✅ | Any TikTok video URL |

<br>

### ✅ Supported URL Formats

```
🔗 https://www.tiktok.com/@username/video/1234567890123456789
🔗 https://vm.tiktok.com/ZNRNw695H
🔗 https://m.tiktok.com/v/1234567890123456789  
🔗 https://vt.tiktok.com/ZSxxxxxxx
```

<br>

### 📤 Example Response

```json
{
  "status": "success",
  "data": {
    "id": "7449869875012345678",
    "title": "Amazing video! 🔥 #trending #viral",
    "author": {
      "username": "creator_name",
      "nickname": "Creator Display Name",
      "avatar": "https://p16-sign.tiktokcdn.com/..."
    },
    "stats": {
      "views": 1500000,
      "likes": 250000,
      "comments": 15000,
      "shares": 50000
    },
    "video": {
      "duration": 15,
      "cover": "https://p16-sign.tiktokcdn.com/...",
      "download_url": "https://v16-webapp.tiktok.com/...",
      "no_watermark_url": "https://v16-webapp.tiktok.com/..."
    },
    "audio": {
      "title": "Original Sound",
      "author": "creator_name", 
      "download_url": "https://sf16-ies-music.tiktokcdn.com/..."
    }
  }
}
```

<br>

### 📊 Status Codes

| Code | Status | Meaning |
|:--:|:--|:--|
| `200` | ✅ Success | All good! Here's your data |
| `400` | ⚠️ Bad Request | Oops! Check your URL |
| `404` | ❌ Not Found | Video doesn't exist |
| `500` | 🔥 Error | Something went wrong on our end |

<br>

---

<br>

<div align="center">

## 💻 Code Examples

### Copy, paste, and you're done! 🎉

<br>

<img src="https://skillicons.dev/icons?i=js,ts,python,php,go,rust,java,cs,ruby,kotlin,swift,dart" alt="Languages">

<br><br>

**18+ Languages Supported** • Click any to see the code! 👇

</div>

<br>

---

### 🟨 JavaScript (Fetch API)

```javascript
const downloadTikTok = async (videoUrl) => {
  const response = await fetch(
    `https://api-social-sooty.vercel.app/api/tiktok?url=${encodeURIComponent(videoUrl)}`
  );
  const { status, data } = await response.json();
  
  if (status === 'success') {
    console.log('📹 Video:', data.title);
    console.log('👤 Author:', `@${data.author.username}`);
    console.log('❤️ Likes:', data.stats.likes.toLocaleString());
    console.log('⬇️ Download:', data.video.no_watermark_url);
  }
  
  return data;
};

// 🎉 Let's go!
downloadTikTok('https://vm.tiktok.com/ZNRNw695H');
```

---

### 🟨 JavaScript (Axios)

```javascript
import axios from 'axios';

const api = axios.create({
  baseURL: 'https://api-social-sooty.vercel.app/api',
  timeout: 30000
});

const downloadTikTok = async (url) => {
  try {
    const { data } = await api.get('/tiktok', { params: { url } });
    
    if (data.status === 'success') {
      const video = data.data;
      console.log(`🎬 ${video.title}`);
      console.log(`👤 @${video.author.username}`);
      console.log(`❤️ ${video.stats.likes.toLocaleString()} likes`);
      console.log(`⬇️ ${video.video.no_watermark_url}`);
      return video;
    }
  } catch (error) {
    console.error('💥 Error:', error.message);
  }
};

// 🚀 Ready to rock!
downloadTikTok('https://vm.tiktok.com/ZNRNw695H');
```

---

### 🔷 TypeScript

```typescript
interface TikTokResponse {
  status: 'success' | 'error';
  data: {
    id: string;
    title: string;
    author: { username: string; nickname: string; avatar: string };
    stats: { views: number; likes: number; comments: number; shares: number };
    video: { duration: number; cover: string; download_url: string; no_watermark_url: string };
    audio: { title: string; author: string; download_url: string };
  };
}

async function downloadTikTok(videoUrl: string): Promise<TikTokResponse['data'] | null> {
  const response = await fetch(
    `https://api-social-sooty.vercel.app/api/tiktok?url=${encodeURIComponent(videoUrl)}`
  );
  
  const result: TikTokResponse = await response.json();
  
  if (result.status === 'success') {
    console.log(`📹 ${result.data.title}`);
    console.log(`👤 @${result.data.author.username}`);
    console.log(`❤️ ${result.data.stats.likes.toLocaleString()} likes`);
    return result.data;
  }
  
  return null;
}

// 💪 Type-safe and ready!
downloadTikTok('https://vm.tiktok.com/ZNRNw695H');
```

---

### 🐍 Python (Requests)

```python
import requests
from typing import Optional, Dict, Any

class TikSaveAPI:
    """🎵 TikSave API - Download TikTok videos without watermark!"""
    
    BASE_URL = "https://api-social-sooty.vercel.app/api/tiktok"
    
    @staticmethod
    def download(video_url: str) -> Optional[Dict[str, Any]]:
        """Download TikTok video information."""
        response = requests.get(
            TikSaveAPI.BASE_URL,
            params={"url": video_url},
            timeout=30
        )
        response.raise_for_status()
        data = response.json()
        
        if data["status"] == "success":
            video = data["data"]
            print(f"🎬 {video['title'][:50]}...")
            print(f"👤 @{video['author']['username']}")
            print(f"❤️ {video['stats']['likes']:,} likes")
            print(f"⬇️ {video['video']['no_watermark_url']}")
            return video
        
        return None

# 🐍 Python power!
video = TikSaveAPI.download("https://vm.tiktok.com/ZNRNw695H")
```

---

### 🐍 Python (Async - aiohttp)

```python
import aiohttp
import asyncio
from typing import Optional, Dict, Any, List

class TikSaveAPIAsync:
    """⚡ Async TikSave API - Super fast batch downloads!"""
    
    BASE_URL = "https://api-social-sooty.vercel.app/api/tiktok"
    
    @staticmethod
    async def download(video_url: str) -> Optional[Dict[str, Any]]:
        async with aiohttp.ClientSession() as session:
            async with session.get(
                TikSaveAPIAsync.BASE_URL,
                params={"url": video_url}
            ) as response:
                data = await response.json()
                return data["data"] if data["status"] == "success" else None
    
    @staticmethod
    async def batch_download(urls: List[str]) -> List[Dict[str, Any]]:
        """🚀 Download multiple videos at once!"""
        tasks = [TikSaveAPIAsync.download(url) for url in urls]
        results = await asyncio.gather(*tasks)
        return [r for r in results if r is not None]

# ⚡ Async is the way!
async def main():
    video = await TikSaveAPIAsync.download("https://vm.tiktok.com/ZNRNw695H")
    if video:
        print(f"🎬 {video['title']}")
        print(f"👤 @{video['author']['username']}")

asyncio.run(main())
```

---

### 🐘 PHP (cURL)

```php
<?php
/**
 * 🎵 TikSave API - PHP Implementation
 * Download TikTok videos without watermark!
 */

class TikSaveAPI {
    private const BASE_URL = 'https://api-social-sooty.vercel.app/api/tiktok';
    
    public static function download(string $videoUrl): ?array {
        $ch = curl_init();
        
        curl_setopt_array($ch, [
            CURLOPT_URL => self::BASE_URL . '?url=' . urlencode($videoUrl),
            CURLOPT_RETURNTRANSFER => true,
            CURLOPT_TIMEOUT => 30,
            CURLOPT_FOLLOWLOCATION => true,
            CURLOPT_HTTPHEADER => ['Accept: application/json']
        ]);
        
        $response = curl_exec($ch);
        $httpCode = curl_getinfo($ch, CURLINFO_HTTP_CODE);
        curl_close($ch);
        
        if ($httpCode !== 200) return null;
        
        $data = json_decode($response, true);
        
        if ($data['status'] === 'success') {
            $video = $data['data'];
            echo "🎬 {$video['title']}\n";
            echo "👤 @{$video['author']['username']}\n";
            echo "❤️ " . number_format($video['stats']['likes']) . " likes\n";
            echo "⬇️ {$video['video']['no_watermark_url']}\n";
            return $video;
        }
        
        return null;
    }
}

// 🐘 PHP ftw!
$video = TikSaveAPI::download('https://vm.tiktok.com/ZNRNw695H');
```

---

### 🐘 PHP (Guzzle)

```php
<?php

require 'vendor/autoload.php';

use GuzzleHttp\Client;
use GuzzleHttp\Exception\GuzzleException;

class TikSaveAPI {
    private Client $client;
    
    public function __construct() {
        $this->client = new Client([
            'base_uri' => 'https://api-social-sooty.vercel.app/api/',
            'timeout' => 30
        ]);
    }
    
    public function download(string $url): ?array {
        try {
            $response = $this->client->get('tiktok', [
                'query' => ['url' => $url]
            ]);
            
            $data = json_decode($response->getBody(), true);
            
            return $data['status'] === 'success' ? $data['data'] : null;
        } catch (GuzzleException $e) {
            echo "💥 Error: " . $e->getMessage();
            return null;
        }
    }
}

// 🎉 Easy peasy!
$api = new TikSaveAPI();
$video = $api->download('https://vm.tiktok.com/ZNRNw695H');
print_r($video);
```

---

### 🐹 Go

```go
package main

import (
    "encoding/json"
    "fmt"
    "net/http"
    "net/url"
)

// 🎵 TikSave API Response structure
type Response struct {
    Status string `json:"status"`
    Data   struct {
        ID     string `json:"id"`
        Title  string `json:"title"`
        Author struct {
            Username string `json:"username"`
            Nickname string `json:"nickname"`
        } `json:"author"`
        Stats struct {
            Views    int64 `json:"views"`
            Likes    int64 `json:"likes"`
            Comments int64 `json:"comments"`
            Shares   int64 `json:"shares"`
        } `json:"stats"`
        Video struct {
            Duration       int    `json:"duration"`
            NoWatermarkURL string `json:"no_watermark_url"`
        } `json:"video"`
        Audio struct {
            Title       string `json:"title"`
            DownloadURL string `json:"download_url"`
        } `json:"audio"`
    } `json:"data"`
}

func DownloadTikTok(videoURL string) (*Response, error) {
    apiURL := fmt.Sprintf(
        "https://api-social-sooty.vercel.app/api/tiktok?url=%s",
        url.QueryEscape(videoURL),
    )
    
    resp, err := http.Get(apiURL)
    if err != nil {
        return nil, err
    }
    defer resp.Body.Close()
    
    var result Response
    if err := json.NewDecoder(resp.Body).Decode(&result); err != nil {
        return nil, err
    }
    
    return &result, nil
}

func main() {
    // 🚀 Go go go!
    video, err := DownloadTikTok("https://vm.tiktok.com/ZNRNw695H")
    if err != nil {
        fmt.Println("💥 Error:", err)
        return
    }
    
    fmt.Printf("🎬 %s\n", video.Data.Title)
    fmt.Printf("👤 @%s\n", video.Data.Author.Username)
    fmt.Printf("❤️ %d likes\n", video.Data.Stats.Likes)
    fmt.Printf("⬇️ %s\n", video.Data.Video.NoWatermarkURL)
}
```

---

### 🦀 Rust

```rust
use reqwest;
use serde::Deserialize;
use anyhow::Result;

/// 🎵 TikSave API - Rust implementation
/// Fast and safe TikTok video downloads!

#[derive(Debug, Deserialize)]
struct ApiResponse {
    status: String,
    data: VideoData,
}

#[derive(Debug, Deserialize)]
struct VideoData {
    id: String,
    title: String,
    author: Author,
    stats: Stats,
    video: Video,
    audio: Audio,
}

#[derive(Debug, Deserialize)]
struct Author { username: String, nickname: String }

#[derive(Debug, Deserialize)]
struct Stats { views: u64, likes: u64, comments: u64, shares: u64 }

#[derive(Debug, Deserialize)]
struct Video { duration: u32, no_watermark_url: String }

#[derive(Debug, Deserialize)]
struct Audio { title: String, download_url: String }

async fn download_tiktok(url: &str) -> Result<VideoData> {
    let api_url = format!(
        "https://api-social-sooty.vercel.app/api/tiktok?url={}",
        urlencoding::encode(url)
    );
    
    let response: ApiResponse = reqwest::get(&api_url)
        .await?
        .json()
        .await?;
    
    Ok(response.data)
}

#[tokio::main]
async fn main() -> Result<()> {
    // 🦀 Rust is blazingly fast!
    let video = download_tiktok("https://vm.tiktok.com/ZNRNw695H").await?;
    
    println!("🎬 {}", video.title);
    println!("👤 @{}", video.author.username);
    println!("❤️ {} likes", video.stats.likes);
    println!("⬇️ {}", video.video.no_watermark_url);
    
    Ok(())
}
```

---

### ☕ Java

```java
import java.net.URI;
import java.net.URLEncoder;
import java.net.http.*;
import java.nio.charset.StandardCharsets;
import com.google.gson.*;

/**
 * 🎵 TikSave API - Java Implementation
 * Download TikTok videos with style!
 */
public class TikSaveAPI {
    private static final String BASE_URL = "https://api-social-sooty.vercel.app/api/tiktok";
    private static final HttpClient client = HttpClient.newHttpClient();
    private static final Gson gson = new Gson();
    
    public static JsonObject download(String videoUrl) throws Exception {
        String url = BASE_URL + "?url=" + URLEncoder.encode(videoUrl, StandardCharsets.UTF_8);
        
        HttpRequest request = HttpRequest.newBuilder()
            .uri(URI.create(url))
            .header("Accept", "application/json")
            .GET()
            .build();
        
        HttpResponse<String> response = client.send(request, HttpResponse.BodyHandlers.ofString());
        JsonObject json = gson.fromJson(response.body(), JsonObject.class);
        
        if (json.get("status").getAsString().equals("success")) {
            JsonObject data = json.getAsJsonObject("data");
            
            System.out.println("🎬 " + data.get("title").getAsString());
            System.out.println("👤 @" + data.getAsJsonObject("author").get("username").getAsString());
            System.out.println("❤️ " + data.getAsJsonObject("stats").get("likes").getAsLong() + " likes");
            System.out.println("⬇️ " + data.getAsJsonObject("video").get("no_watermark_url").getAsString());
            
            return data;
        }
        
        return null;
    }
    
    public static void main(String[] args) throws Exception {
        // ☕ Java developers rejoice!
        download("https://vm.tiktok.com/ZNRNw695H");
    }
}
```

---

### 💜 C# / .NET

```csharp
using System.Text.Json;
using System.Web;

/// <summary>
/// 🎵 TikSave API - C# Implementation
/// Modern .NET way to download TikTok videos!
/// </summary>
class TikSaveAPI
{
    private static readonly HttpClient _client = new();
    private const string BaseUrl = "https://api-social-sooty.vercel.app/api/tiktok";
    
    public static async Task<JsonElement?> DownloadAsync(string videoUrl)
    {
        var url = $"{BaseUrl}?url={HttpUtility.UrlEncode(videoUrl)}";
        var response = await _client.GetStringAsync(url);
        var json = JsonDocument.Parse(response).RootElement;
        
        if (json.GetProperty("status").GetString() == "success")
        {
            var data = json.GetProperty("data");
            
            Console.WriteLine($"🎬 {data.GetProperty("title").GetString()}");
            Console.WriteLine($"👤 @{data.GetProperty("author").GetProperty("username").GetString()}");
            Console.WriteLine($"❤️ {data.GetProperty("stats").GetProperty("likes").GetInt64():N0} likes");
            Console.WriteLine($"⬇️ {data.GetProperty("video").GetProperty("no_watermark_url").GetString()}");
            
            return data;
        }
        
        return null;
    }
    
    // 💜 C# is elegant!
    static async Task Main() => await DownloadAsync("https://vm.tiktok.com/ZNRNw695H");
}
```

---

### 💎 Ruby

```ruby
require 'net/http'
require 'json'
require 'uri'

# 🎵 TikSave API - Ruby Implementation
# Download TikTok videos the Ruby way!

module TikSaveAPI
  BASE_URL = 'https://api-social-sooty.vercel.app/api/tiktok'
  
  def self.download(video_url)
    uri = URI("#{BASE_URL}?url=#{URI.encode_www_form_component(video_url)}")
    response = Net::HTTP.get(uri)
    data = JSON.parse(response)
    
    return nil unless data['status'] == 'success'
    
    video = data['data']
    puts "🎬 #{video['title'][0..50]}..."
    puts "👤 @#{video['author']['username']}"
    puts "❤️ #{video['stats']['likes'].to_s.reverse.gsub(/(\d{3})(?=\d)/, '\\1,').reverse} likes"
    puts "⬇️ #{video['video']['no_watermark_url']}"
    
    video
  end
end

# 💎 Ruby is beautiful!
TikSaveAPI.download('https://vm.tiktok.com/ZNRNw695H')
```

---

### 🔶 Kotlin

```kotlin
import kotlinx.coroutines.*
import kotlinx.serialization.*
import kotlinx.serialization.json.*
import java.net.URL
import java.net.URLEncoder

/**
 * 🎵 TikSave API - Kotlin Implementation
 * Modern, concise, and powerful!
 */

@Serializable
data class TikTokResponse(val status: String, val data: VideoData)

@Serializable
data class VideoData(
    val id: String,
    val title: String,
    val author: Author,
    val stats: Stats,
    val video: Video
)

@Serializable
data class Author(val username: String, val nickname: String)

@Serializable
data class Stats(val views: Long, val likes: Long, val comments: Long, val shares: Long)

@Serializable
data class Video(val duration: Int, val no_watermark_url: String)

suspend fun downloadTikTok(videoUrl: String): VideoData? = withContext(Dispatchers.IO) {
    val url = "https://api-social-sooty.vercel.app/api/tiktok?url=${URLEncoder.encode(videoUrl, "UTF-8")}"
    val response = URL(url).readText()
    val result = Json { ignoreUnknownKeys = true }.decodeFromString<TikTokResponse>(response)
    
    if (result.status == "success") result.data else null
}

fun main() = runBlocking {
    // 🔶 Kotlin is awesome!
    downloadTikTok("https://vm.tiktok.com/ZNRNw695H")?.let { video ->
        println("🎬 ${video.title}")
        println("👤 @${video.author.username}")
        println("❤️ ${video.stats.likes} likes")
        println("⬇️ ${video.video.no_watermark_url}")
    }
}
```

---

### 🦢 Swift

```swift
import Foundation

/// 🎵 TikSave API - Swift Implementation
/// iOS/macOS ready!

struct TikTokResponse: Codable {
    let status: String
    let data: VideoData
}

struct VideoData: Codable {
    let id, title: String
    let author: Author
    let stats: Stats
    let video: Video
    let audio: Audio
}

struct Author: Codable { let username, nickname: String }
struct Stats: Codable { let views, likes, comments, shares: Int }
struct Video: Codable { let duration: Int; let no_watermark_url: String }
struct Audio: Codable { let title: String; let download_url: String }

func downloadTikTok(url videoURL: String) async throws -> VideoData {
    let encoded = videoURL.addingPercentEncoding(withAllowedCharacters: .urlQueryAllowed)!
    let url = URL(string: "https://api-social-sooty.vercel.app/api/tiktok?url=\(encoded)")!
    
    let (data, _) = try await URLSession.shared.data(from: url)
    let response = try JSONDecoder().decode(TikTokResponse.self, from: data)
    
    return response.data
}

// 🦢 Swift is powerful!
Task {
    do {
        let video = try await downloadTikTok(url: "https://vm.tiktok.com/ZNRNw695H")
        print("🎬 \(video.title)")
        print("👤 @\(video.author.username)")
        print("❤️ \(video.stats.likes) likes")
        print("⬇️ \(video.video.no_watermark_url)")
    } catch {
        print("💥 Error: \(error)")
    }
}
```

---

### 🎯 Dart / Flutter

```dart
import 'dart:convert';
import 'package:http/http.dart' as http;

/// 🎵 TikSave API - Dart/Flutter Implementation
/// Perfect for mobile apps!

class TikSaveAPI {
  static const _baseUrl = 'https://api-social-sooty.vercel.app/api/tiktok';
  
  static Future<Map<String, dynamic>?> download(String videoUrl) async {
    final response = await http.get(
      Uri.parse('$_baseUrl?url=${Uri.encodeComponent(videoUrl)}'),
    );
    
    if (response.statusCode != 200) return null;
    
    final data = json.decode(response.body);
    
    if (data['status'] == 'success') {
      final video = data['data'];
      print('🎬 ${video['title']}');
      print('👤 @${video['author']['username']}');
      print('❤️ ${video['stats']['likes']} likes');
      print('⬇️ ${video['video']['no_watermark_url']}');
      return video;
    }
    
    return null;
  }
}

// 🎯 Dart is versatile!
void main() async {
  await TikSaveAPI.download('https://vm.tiktok.com/ZNRNw695H');
}
```

---

### 🐚 cURL / Bash

```bash
#!/bin/bash

# 🎵 TikSave API - Shell Script
# Command line power!

# Simple one-liner
curl -s "https://api-social-sooty.vercel.app/api/tiktok?url=https://vm.tiktok.com/ZNRNw695H" | jq

# Pretty output function
download_tiktok() {
    local url="$1"
    local encoded=$(python3 -c "import urllib.parse; print(urllib.parse.quote('$url'))")
    local response=$(curl -s "https://api-social-sooty.vercel.app/api/tiktok?url=$encoded")
    
    echo ""
    echo "╔═══════════════════════════════════════════════════════════╗"
    echo "║           🎵 TikSave API Response                         ║"
    echo "╠═══════════════════════════════════════════════════════════╣"
    echo "║ 🎬 Title:  $(echo $response | jq -r '.data.title[:45]')..."
    echo "║ 👤 Author: @$(echo $response | jq -r '.data.author.username')"
    echo "║ 👀 Views:  $(echo $response | jq -r '.data.stats.views')"
    echo "║ ❤️ Likes:  $(echo $response | jq -r '.data.stats.likes')"
    echo "╚═══════════════════════════════════════════════════════════╝"
    echo ""
}

# 🐚 Terminal warriors!
download_tiktok "https://vm.tiktok.com/ZNRNw695H"
```

---

### ⚡ PowerShell

```powershell
<#
.SYNOPSIS
    🎵 TikSave API - PowerShell Implementation
    
.DESCRIPTION
    Download TikTok videos without watermark using PowerShell!
#>

function Get-TikTokVideo {
    param(
        [Parameter(Mandatory)]
        [string]$Url
    )
    
    $encoded = [System.Web.HttpUtility]::UrlEncode($Url)
    $apiUrl = "https://api-social-sooty.vercel.app/api/tiktok?url=$encoded"
    
    try {
        $response = Invoke-RestMethod -Uri $apiUrl -Method Get
        
        if ($response.status -eq "success") {
            $video = $response.data
            
            Write-Host ""
            Write-Host "🎬 $($video.title)" -ForegroundColor Cyan
            Write-Host "👤 @$($video.author.username)" -ForegroundColor Green
            Write-Host "❤️ $($video.stats.likes.ToString('N0')) likes" -ForegroundColor Red
            Write-Host "⬇️ $($video.video.no_watermark_url)" -ForegroundColor Blue
            Write-Host ""
            
            return $video
        }
    }
    catch {
        Write-Error "💥 Error: $_"
    }
}

# ⚡ PowerShell is powerful!
Get-TikTokVideo -Url "https://vm.tiktok.com/ZNRNw695H"
```

---

### 🔷 R

```r
# 🎵 TikSave API - R Implementation
# Data science meets TikTok!

library(httr)
library(jsonlite)

download_tiktok <- function(video_url) {
  response <- GET(
    "https://api-social-sooty.vercel.app/api/tiktok",
    query = list(url = video_url),
    timeout(30)
  )
  
  data <- fromJSON(content(response, "text", encoding = "UTF-8"))
  
  if (data$status == "success") {
    video <- data$data
    
    cat("🎬", video$title, "\n")
    cat("👤 @", video$author$username, "\n")
    cat("❤️", format(video$stats$likes, big.mark = ","), "likes\n")
    cat("⬇️", video$video$no_watermark_url, "\n")
    
    return(video)
  }
  
  return(NULL)
}

# 🔷 R is for researchers!
video <- download_tiktok("https://vm.tiktok.com/ZNRNw695H")
```

---

### 🐪 Perl

```perl
#!/usr/bin/perl

# 🎵 TikSave API - Perl Implementation
# Old school but still rocks!

use strict;
use warnings;
use LWP::UserAgent;
use JSON;
use URI::Escape;

sub download_tiktok {
    my ($video_url) = @_;
    
    my $ua = LWP::UserAgent->new(timeout => 30);
    my $api_url = "https://api-social-sooty.vercel.app/api/tiktok?url=" . uri_escape($video_url);
    
    my $response = $ua->get($api_url);
    
    die "💥 Request failed: " . $response->status_line unless $response->is_success;
    
    my $data = decode_json($response->content);
    
    if ($data->{status} eq 'success') {
        my $video = $data->{data};
        
        print "🎬 $video->{title}\n";
        print "👤 \@$video->{author}{username}\n";
        print "❤️ $video->{stats}{likes} likes\n";
        print "⬇️ $video->{video}{no_watermark_url}\n";
        
        return $video;
    }
    
    return undef;
}

# 🐪 Perl still got it!
my $video = download_tiktok("https://vm.tiktok.com/ZNRNw695H");
```

---

### 💧 Elixir

```elixir
# 🎵 TikSave API - Elixir Implementation
# Functional programming FTW!

defmodule TikSaveAPI do
  @base_url "https://api-social-sooty.vercel.app/api/tiktok"
  
  def download(video_url) do
    url = "#{@base_url}?url=#{URI.encode_www_form(video_url)}"
    
    case HTTPoison.get(url, [], timeout: 30_000) do
      {:ok, %{status_code: 200, body: body}} ->
        data = Jason.decode!(body)
        
        if data["status"] == "success" do
          video = data["data"]
          
          IO.puts "🎬 #{video["title"]}"
          IO.puts "👤 @#{video["author"]["username"]}"
          IO.puts "❤️ #{video["stats"]["likes"]} likes"
          IO.puts "⬇️ #{video["video"]["no_watermark_url"]}"
          
          {:ok, video}
        else
          {:error, :failed}
        end
        
      {:error, %{reason: reason}} ->
        {:error, reason}
    end
  end
end

# 💧 Elixir is magical!
TikSaveAPI.download("https://vm.tiktok.com/ZNRNw695H")
```

---

### 🌐 HTML + JavaScript (Complete Web App)

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>🎵 TikSave Downloader</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { 
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      font-family: system-ui, -apple-system, sans-serif;
      background: linear-gradient(135deg, #0f0f23 0%, #1a1a3e 100%);
      color: #fff;
    }
    .card {
      background: rgba(255, 255, 255, 0.05);
      backdrop-filter: blur(20px);
      border-radius: 24px;
      padding: 2.5rem;
      width: min(90%, 450px);
      border: 1px solid rgba(255, 255, 255, 0.1);
      box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.5);
    }
    h1 { text-align: center; margin-bottom: 0.5rem; font-size: 2rem; }
    .subtitle { text-align: center; color: #888; margin-bottom: 2rem; }
    input {
      width: 100%;
      padding: 1rem 1.25rem;
      border: 2px solid rgba(255, 255, 255, 0.1);
      border-radius: 12px;
      background: rgba(0, 0, 0, 0.3);
      color: #fff;
      font-size: 1rem;
      margin-bottom: 1rem;
      transition: border-color 0.2s;
    }
    input:focus { outline: none; border-color: #FF0050; }
    input::placeholder { color: rgba(255, 255, 255, 0.5); }
    button {
      width: 100%;
      padding: 1rem;
      border: none;
      border-radius: 12px;
      background: linear-gradient(135deg, #FF0050, #00F2EA);
      color: #fff;
      font-size: 1.1rem;
      font-weight: 600;
      cursor: pointer;
      transition: transform 0.2s, box-shadow 0.2s;
    }
    button:hover { 
      transform: translateY(-2px); 
      box-shadow: 0 10px 40px rgba(255, 0, 80, 0.4); 
    }
    button:active { transform: translateY(0); }
    #result { 
      margin-top: 1.5rem; 
      padding: 1.25rem; 
      background: rgba(0, 0, 0, 0.3); 
      border-radius: 12px;
      display: none;
    }
    #result p { margin-bottom: 0.75rem; }
    .download-link {
      display: inline-block;
      margin-top: 0.5rem;
      padding: 0.75rem 1.5rem;
      background: #00F2EA;
      color: #000;
      text-decoration: none;
      border-radius: 8px;
      font-weight: 600;
      transition: transform 0.2s;
    }
    .download-link:hover { transform: translateY(-2px); }
    .audio-link { background: #FF0050; color: #fff; margin-left: 0.5rem; }
  </style>
</head>
<body>
  <div class="card">
    <h1>🎵 TikSave</h1>
    <p class="subtitle">Download TikTok videos without watermark!</p>
    <input type="text" id="url" placeholder="Paste TikTok URL here...">
    <button onclick="download()">⬇️ Download Video</button>
    <div id="result"></div>
  </div>

  <script>
    async function download() {
      const url = document.getElementById('url').value.trim();
      const result = document.getElementById('result');
      
      if (!url) {
        alert('🤔 Please enter a TikTok URL!');
        return;
      }
      
      result.style.display = 'block';
      result.innerHTML = '⏳ Fetching video info...';
      
      try {
        const response = await fetch(
          `https://api-social-sooty.vercel.app/api/tiktok?url=${encodeURIComponent(url)}`
        );
        const { status, data } = await response.json();
        
        if (status === 'success') {
          result.innerHTML = `
            <p><strong>🎬 ${data.title.substring(0, 60)}...</strong></p>
            <p>👤 @${data.author.username}</p>
            <p>❤️ ${data.stats.likes.toLocaleString()} likes • 👀 ${data.stats.views.toLocaleString()} views</p>
            <a class="download-link" href="${data.video.no_watermark_url}" target="_blank">
              ⬇️ Download Video
            </a>
            <a class="download-link audio-link" href="${data.audio.download_url}" target="_blank">
              🎵 Download Audio
            </a>
          `;
        } else {
          result.innerHTML = '❌ Video not found or unavailable';
        }
      } catch (error) {
        result.innerHTML = '💥 Error: ' + error.message;
      }
    }
    
    document.getElementById('url').addEventListener('keypress', (e) => {
      if (e.key === 'Enter') download();
    });
  </script>
</body>
</html>
```

<br>

---

<br>

<div align="center">

## 🛠️ Tech Stack

| | Technology | Purpose |
|:--:|:--|:--|
| <img src="https://skillicons.dev/icons?i=vercel" width="30"> | **Vercel** | Hosting & Edge |
| <img src="https://skillicons.dev/icons?i=nodejs" width="30"> | **Node.js** | Runtime |
| <img src="https://skillicons.dev/icons?i=express" width="30"> | **Express** | Framework |
| <img src="https://skillicons.dev/icons?i=ts" width="30"> | **TypeScript** | Type Safety |
| <img src="https://skillicons.dev/icons?i=react" width="30"> | **React** | Frontend |
| <img src="https://skillicons.dev/icons?i=tailwind" width="30"> | **Tailwind** | Styling |

</div>

<br>

---

<br>

<div align="center">

## 👥 Meet The Team

<table>
<tr>
<td align="center" width="350">
<br>
<a href="https://github.com/sychoxhassan">
<img src="https://github.com/sychoxhassan.png" width="140" style="border-radius: 50%; border: 4px solid #FF0050;" alt="Creator">
</a>
<br><br>
<h3>👑 Sychox2006</h3>
<br><br>
<sub>🚀 Building awesome things!</sub>
<br><br>
<a href="https://github.com/sychoxhassan">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
</a>
<br><br>
</td>
<td align="center" width="350">
<br>
<a href="https://github.com/cybershieldpk">
<img src="https://github.com/cybershieldpk.png" width="140" style="border-radius: 50%; border: 4px solid #00F2EA;" alt="Contributor">
</a>
<br><br>
<h3>⭐ CyberSheildPK</h3>
<br><br>
<sub>💡 Making ideas happen!</sub>
<br><br>
<a href="https://github.com/cybershieldpk">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
</a>
<br><br>
</td>
</tr>
</table>

</div>

<br>

---

## 💬 Need Help?

<br>

[![Report Bug](https://img.shields.io/badge/Found%20a%20Bug-Report%20It-FF0050?style=for-the-badge&labelColor=0D1117)](https://github.com/sychoxhassan/TikTokApiDocumentation/issues)

[![Request Feature](https://img.shields.io/badge/Have%20an%20Idea-Share%20It-00F2EA?style=for-the-badge&labelColor=0D1117)](https://t.me/Sychox2006)

[![Documentation](https://img.shields.io/badge/Need%20Docs-Read%20Here-7C3AED?style=for-the-badge&labelColor=0D1117)](https://tiktokapidocumentation.vercel.app)

<br>

---

<br>

### ⭐ If you like this project, give it a star! ⭐

<img src="https://img.shields.io/github/stars/sychoxhassan/TikTokApiDocumentation?style=for-the-badge&logo=github&labelColor=0D1117&color=FFD700" alt="Stars">
<img src="https://img.shields.io/github/forks/sychoxhassan/TikTokApiDocumentation?style=for-the-badge&logo=github&labelColor=0D1117&color=00D4AA" alt="Forks">
<img src="https://img.shields.io/github/watchers/sychoxhassan/TikTokApiDocumentation?style=for-the-badge&logo=github&labelColor=0D1117&color=00F2EA" alt="Watchers">

<br><br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=100&section=footer" width="100%">

<br>

**Made By Sychoxhassan**

<sub>© 2025 TikSave API • All Rights Reserved</sub>

<br>

<img src="https://user-images.githubusercontent.com/74038190/212284158-e840e285-664b-44d7-b79b-e264b5e54825.gif" width="400">

</div>
