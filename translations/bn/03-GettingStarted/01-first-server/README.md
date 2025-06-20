<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "f01d4263fc6eec331615fef42429b720",
  "translation_date": "2025-06-18T18:18:03+00:00",
  "source_file": "03-GettingStarted/01-first-server/README.md",
  "language_code": "bn"
}
-->
### -2- একটি প্রকল্প তৈরি করুন

এখন যেহেতু আপনার SDK ইনস্টল হয়ে গেছে, চলুন পরবর্তী ধাপে একটি প্রকল্প তৈরি করি:

### -3- প্রকল্প ফাইল তৈরি করুন

### -4- সার্ভারের কোড লিখুন

### -5- একটি টুল এবং একটি রিসোর্স যোগ করা

নিচের কোডটি যোগ করে একটি টুল এবং একটি রিসোর্স যোগ করুন:

### -6- চূড়ান্ত কোড

সার্ভার চালু করার জন্য প্রয়োজনীয় শেষ কোডটি যোগ করা যাক:

### -7- সার্ভার পরীক্ষা করুন

নিচের কমান্ডটি ব্যবহার করে সার্ভার শুরু করুন:

### -8- ইন্সপেক্টর ব্যবহার করে চালান

ইন্সপেক্টর একটি চমৎকার টুল যা আপনার সার্ভার চালু করে এবং এর সাথে ইন্টারঅ্যাক্ট করার সুযোগ দেয়, যাতে আপনি পরীক্ষা করতে পারেন এটি ঠিকমতো কাজ করছে কিনা। চলুন এটি চালু করি:

> [!NOTE]
> "command" ফিল্ডে এটি ভিন্ন দেখাতে পারে কারণ এটি আপনার নির্দিষ্ট রানটাইমের জন্য সার্ভার চালানোর কমান্ড ধারণ করে।

আপনি নিম্নলিখিত ব্যবহারকারী ইন্টারফেস দেখতে পাবেন:

![Connect](../../../../translated_images/connect.141db0b2bd05f096fb1dd91273771fd8b2469d6507656c3b0c9df4b3c5473929.bn.png)

1. "Connect" বাটনে ক্লিক করে সার্ভারের সাথে সংযোগ করুন  
   একবার সংযোগ হয়ে গেলে, আপনি নিম্নলিখিত দেখতে পাবেন:

   ![Connected](../../../../translated_images/connected.73d1e042c24075d386cacdd4ee7cd748c16364c277d814e646ff2f7b5eefde85.bn.png)

2. "Tools" এবং "listTools" নির্বাচন করুন, আপনি "Add" দেখতে পাবেন, "Add" নির্বাচন করুন এবং প্যারামিটার মানগুলি পূরণ করুন।

   আপনি নিচের রেসপন্সটি দেখতে পাবেন, অর্থাৎ "add" টুল থেকে একটি ফলাফল:

   ![Result of running add](../../../../translated_images/ran-tool.a5a6ee878c1369ec1e379b81053395252a441799dbf23416c36ddf288faf8249.bn.png)

অভিনন্দন, আপনি সফলভাবে আপনার প্রথম সার্ভার তৈরি ও চালাতে পেরেছেন!

### অফিসিয়াল SDK গুলো

MCP বিভিন্ন ভাষার জন্য অফিসিয়াল SDK প্রদান করে:

- [C# SDK](https://github.com/modelcontextprotocol/csharp-sdk) - মাইক্রোসফটের সহযোগিতায় রক্ষণাবেক্ষণ
- [Java SDK](https://github.com/modelcontextprotocol/java-sdk) - Spring AI এর সহযোগিতায় রক্ষণাবেক্ষণ
- [TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk) - অফিসিয়াল TypeScript ইমপ্লিমেন্টেশন
- [Python SDK](https://github.com/modelcontextprotocol/python-sdk) - অফিসিয়াল Python ইমপ্লিমেন্টেশন
- [Kotlin SDK](https://github.com/modelcontextprotocol/kotlin-sdk) - অফিসিয়াল Kotlin ইমপ্লিমেন্টেশন
- [Swift SDK](https://github.com/modelcontextprotocol/swift-sdk) - Loopwork AI এর সহযোগিতায় রক্ষণাবেক্ষণ
- [Rust SDK](https://github.com/modelcontextprotocol/rust-sdk) - অফিসিয়াল Rust ইমপ্লিমেন্টেশন

## মূল বিষয়সমূহ

- MCP ডেভেলপমেন্ট পরিবেশ তৈরি করা ভাষা-নির্দিষ্ট SDK গুলো দিয়ে সহজ
- MCP সার্ভার তৈরি করতে হয় টুল তৈরি ও রেজিস্টার করে স্পষ্ট স্কিমা সহ
- পরীক্ষা ও ডিবাগিং MCP ইমপ্লিমেন্টেশনের জন্য অত্যন্ত গুরুত্বপূর্ণ

## নমুনা

- [Java Calculator](../samples/java/calculator/README.md)
- [.Net Calculator](../../../../03-GettingStarted/samples/csharp)
- [JavaScript Calculator](../samples/javascript/README.md)
- [TypeScript Calculator](../samples/typescript/README.md)
- [Python Calculator](../../../../03-GettingStarted/samples/python)

## অ্যাসাইনমেন্ট

আপনার পছন্দের একটি টুল দিয়ে একটি সহজ MCP সার্ভার তৈরি করুন:

1. আপনার পছন্দের ভাষায় টুলটি ইমপ্লিমেন্ট করুন (.NET, Java, Python, অথবা JavaScript)।
2. ইনপুট প্যারামিটার এবং রিটার্ন ভ্যালু নির্ধারণ করুন।
3. ইন্সপেক্টর টুল চালিয়ে নিশ্চিত করুন সার্ভার ঠিকভাবে কাজ করছে।
4. বিভিন্ন ইনপুট দিয়ে ইমপ্লিমেন্টেশন পরীক্ষা করুন।

## সমাধান

[Solution](./solution/README.md)

## অতিরিক্ত সম্পদ

- [Azure-তে Model Context Protocol ব্যবহার করে এজেন্ট তৈরি](https://learn.microsoft.com/azure/developer/ai/intro-agents-mcp)
- [Azure Container Apps-এ রিমোট MCP (Node.js/TypeScript/JavaScript)](https://learn.microsoft.com/samples/azure-samples/mcp-container-ts/mcp-container-ts/)
- [.NET OpenAI MCP এজেন্ট](https://learn.microsoft.com/samples/azure-samples/openai-mcp-agent-dotnet/openai-mcp-agent-dotnet/)

## পরবর্তী ধাপ

পরবর্তী: [MCP ক্লায়েন্ট দিয়ে শুরু করা](/03-GettingStarted/02-client/README.md)

**অস্বীকৃতি**:  
এই নথিটি AI অনুবাদ সেবা [Co-op Translator](https://github.com/Azure/co-op-translator) ব্যবহার করে অনূদিত হয়েছে। আমরা যথাসাধ্য সঠিকতার জন্য চেষ্টা করি, তবে স্বয়ংক্রিয় অনুবাদে ত্রুটি বা ভুল থাকতে পারে তা অনুগ্রহ করে বিবেচনা করুন। মূল নথিটি তার নিজস্ব ভাষায় কর্তৃত্বপূর্ণ উৎস হিসেবে গণ্য করা উচিত। গুরুত্বপূর্ণ তথ্যের জন্য পেশাদার মানব অনুবাদ গ্রহণ করার পরামর্শ দেওয়া হয়। এই অনুবাদের ব্যবহারের ফলে কোনো ভুল বোঝাবুঝি বা ভুল ব্যাখ্যার জন্য আমরা দায়ী নই।