---
layout: about
title: about
permalink: /
subtitle: <a href='https://www.gatech.edu/'>Georgia Institute Of Technology</a>
nav: false

profile:
  align: right
  image: prof_pic_color.jpeg
  image_circular: false
  more_info:

news: false
latest_posts: false
selected_papers: false
social: true
---

## Summary

Georgia Tech MSCS student (Systems for ML, GPA 4.0) focused on building reliable data and ML systems. Previously earned a BE in Computer Science with Honors in ML (GPA 9.2/10.0) from COEP Technological University. I enjoy solving performance, reliability, and scalability problems across distributed systems, ML infrastructure, and backend platforms.

**Contact:** [Email](mailto:okhare6@gatech.edu) · [LinkedIn](https://www.linkedin.com/in/omkhare) · [GitHub](https://github.com/OmKhare)

<style>
.resume-heading {
  font-size: 1.1rem;
  font-weight: 700;
}
</style>

## Education

- **<span class="resume-heading">Georgia Institute of Technology</span>**  
  MS in Computer Science — GPA: 4.0/4.0 (Aug 2024 – May 2026)  
  Atlanta, GA  
  - Coursework: Systems for ML, Big Data Systems, Database System Implementation, Deep Learning, AI
- **<span class="resume-heading">COEP Technological University</span>**  
  BE in Computer Science (Honors in ML) — GPA: 9.2/10.0 (Aug 2020 – May 2024)  
  Pune, India  
  - Coursework: Data Structures, Algorithms, Computer Networks, Operating Systems, Information Retrieval, ML

## Experience

- **<span class="resume-heading">Cloudflare</span>**  
  Software Engineer Intern (May 2025 – Aug 2025) — Austin, USA  
  - Designed and shipped a new operation for vector database in Rust, to iterate over vectors in an index with snapshot consistency, enabling efficient listing of up to 5 million vector IDs using pagination. Released in production via REST, CLI, and SDK interfaces.
  - Moved upsert/insert operations from the core server to Cloudflare’s globally distributed edge metals eliminating control-plane round-trips, reducing timeouts by 30% and fully eliminating rate-limiting errors (down from 2,400 per week to 0).
  - Rearchitected control flow through Edge Auth to retain 100% of validation and business logic during the edge migration, ensuring full feature parity and zero customer-impact.
- **<span class="resume-heading">Systems for AI Lab (SAIL), Georgia Tech</span>**  
  Research Assistant (Jan 2025 – May 2025) — Atlanta, USA  
  - Implemented dynamic resource allocation and checkpointing strategies for large vision models, reducing retraining costs by 35%.
  - Designed weight sharing across 3–6 decoder layers in Mask2Former, achieving 25–30% faster training without accuracy loss.
  - Enhanced semantic segmentation accuracy by 1.9% on Cityscapes and 2.3% on COCO, achieving state-of-the-art results.
- **<span class="resume-heading">Deutsche Bank</span>**  
  Software Development Intern (May 2023 – July 2023) — Pune, India  
  - Created a sentiment analysis pipeline with LLM-based summarization, using GPT-4, increasing content engagement by 20%.
  - Deployed the solution on AWS (EC2, S3, Lambda), enabling efficient integration of sentiment summaries with knowledge articles.
  - Built responsive React.js frontend with dynamic UI components to deliver real-time analytics.
  - Introduced “Related articles” section using vector embeddings, improving content discovery and reducing search time by 20%.
- **<span class="resume-heading">Samsung Research</span>**  
  Software Research Intern (Jan 2023 – May 2023) — Remote, India  
  - Architected an On-Device Lightweight Graph Database by implementing a SPARQL parser for RDF query optimization that stored 1 Million triples with TURTLE and NTRIPLE file support.
  - Reduced query processing time by 60% and outperformed expected performance metrics of 1 ms query plan execution and 20k minimum operations per second.
  - Created locks, multi-threading and other ACID properties while supporting up to 10 parallel connections to DB.

## Projects

- **<span class="resume-heading">StudyBuddy AI App</span>** (Jan 2025 – May 2025)
  - Built a Swift framework with 10 reusable APIs for search and summarization, adopted by 15+ iOS Club members.
  - Developed a SwiftUI app used by 40+ students to ask natural language questions about notes, calendars, and dining menus.
  - Implemented an agentic workflow that planned multi-step actions (search → retrieve → combine), improving response accuracy and task success by 25%.
- **<span class="resume-heading">FinSight — Mixed RAG Financial Analytics</span>** (Aug 2024 – Nov 2024)
  - Developed an AI-powered financial advisory tool, FinSight, by fine-tuning multimodal LLMs with over 9,000 data points using advanced prompt engineering techniques, for descriptive stock market predictions and analysis.
  - Constructed a retrieval-augmented generation (RAG) system, enhancing the accuracy of market trend predictions by combining textual & visual financial insights and found it to be better than current open-source models like FinGPT by 12%.
