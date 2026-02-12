---
permalink: /
title: "Welcome to DL 2026"
layout: splash
header:
  overlay_image: /assets/images/big.jpg
  overlay_filter: "0.5" # darkens image for better text readability
  overlay_color: "#000" # black overlay (optional)
excerpt: "July 17-19, 2026 · Lisbon, Portugal"
---

    

<p>The <a href="https://dl.kr.org/">DL workshop</a> is the major annual event of the description logic research community. It is the forum in which those interested in description logics, both from academia and industry, meet to discuss ideas, share information and compare experiences.</p>
<p>The 39th International Workshop on Description Logics will be held in Lisbon, Portugal, from July 17 to July 19, 2026. It will be co-located with several events as part of <a href="https://www.floc26.org/">FLoC 2026</a>, including <a href="https://kr.org/KR2026/">KR 2026</a> and NMR 2026.</p>


## Invited Speakers 
<p>We're honored to host these distinguished experts at our DL workshop. Each speaker will share their expertise in a keynote talk followed by a discussion session. </p>


<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Invited Speakers | DL Workshop </title>
    <style>
        .speakers-container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
            gap: 30px;
        }
        
        .speaker-card {
            background-color: white;
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.08);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            cursor: pointer;
            position: relative;
        }
        
        .speaker-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.15);
        }
        
        .speaker-img {
            width: 100%;
            height: 280px;
            object-fit: cover;
            display: block;
        }
        
        .speaker-info {
            padding: 25px;
        }
        
        .speaker-name {            
            font-size: 1.5rem;
            margin-top: 0px;
        }
        
        .speaker-affiliation {
            font-size: 1rem;
            margin-bottom: 15px;
            display: flex;
            align-items: center;
        }
        
        .speaker-affiliation i {
            margin-right: 8px;
        }
        
        .speaker-talk {
            font-size: 0.95rem;
            border-top: 1px dashed #e0e0e0;
            padding-top: 15px;
            line-height: 1.5;
        }
        
        .talk-title {
            font-weight: 600;
            margin-bottom: 5px;
        }
                
        .sponsors-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 30px;
            align-items: center;
        }
        
        .sponsor-logo {
            background-color: white;
            border-radius: 12px;
            overflow: hidden;
            padding: 25px;
            display: flex;
            align-items: center;
            justify-content: center;
            height: 140px;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.08);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            border: 1px solid #e0e0e0;
            cursor: pointer;
            position: relative;
        }
        
        .sponsor-logo:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.15);
            .tooltiptext {
                visibility: visible;
            }
        }
        
        .sponsor-logo img {
            max-width: 100%;
            max-height: 80px;
            object-fit: contain;
        }

        /* Tooltip text */
        .tooltiptext {
          visibility: hidden; /* Hidden by default */
          background-color: white;
          text-align: left;
          position: absolute;
          left: 10px;
          z-index: 1; /* Ensure tooltip is displayed above content */
        }
        
        @media (max-width: 480px) {
            .speakers-container {
                grid-template-columns: 1fr;
            }
            
            .sponsors-grid {
                grid-template-columns: 1fr;
            }
            
            .sponsor-logo {
                height: 100px;
                padding: 15px;
            }
    </style>
</head>
<body>   
    <section class="speakers-container">
        <!-- Speaker 1 -->
        <div class="speaker-card" onclick="window.open('https://tommiemeyer.org.za/', '_blank')">
            <img src="/assets/images/TM.jpg" alt="Tommie Meyer Picture" class="speaker-img">
            <div class="speaker-info">
                <h4 class="speaker-name">Tommie Meyer</h4>
                <!--<p>Professor of Computer Science</p>-->
                <p class="speaker-affiliation"><i class="fas fa-university"></i>University of Cape Town</p>
                <div class="speaker-talk">
                    <p class="talk-title">DL & NMR: A Joint Talk</p>
                    <p></p>
                </div> 
            </div>
        </div>
        
        <!-- Speaker 2 -->
        <div class="speaker-card" onclick="window.open('https://lat.inf.tu-dresden.de/~stefborg/', '_blank')">
            <img src="/assets/images/SB.jpg" alt="Stefan Borgwardt" class="speaker-img">
            <div class="speaker-info">
                <h3 class="speaker-name">Stefan Borgwardt</h3>
                <!--<p class="speaker-title">Director of Genomics Research</p>-->
                <p class="speaker-affiliation"><i class="fas fa-university"></i>TU Dresden, Germany</p>
               <!-- <div class="speaker-talk">
                    <p class="talk-title">CRISPR and Beyond: Gene Editing Frontiers</p>
                    <p>Recent advances in gene editing technologies and their ethical implications for future medical treatments.</p>
                </div>-->
            </div>
        </div> 
        
        <!-- Speaker 3 -->
       <!-- <div class="speaker-card">
            <img src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=870&q=80" alt="Dr. Kenji Tanaka" class="speaker-img">
            <div class="speaker-info">
                <h3 class="speaker-name">Dr. Kenji Tanaka</h3>
                <p class="speaker-title">Quantum Computing Researcher</p>
                <p class="speaker-affiliation"><i class="fas fa-university"></i> University of Tokyo, Japan</p>
                <div class="speaker-talk">
                    <p class="talk-title">Quantum Algorithms for Real-World Problems</p>
                    <p>Developing quantum computing solutions for optimization challenges in logistics, finance, and material science.</p>
                </div>
            </div>
        </div> -->
    </section>
</body>

<!-- Sponsors Section -->
## Our Sponsors
<p>We extend our sincere gratitude to our sponsors for their generous support. Their contributions help advance the field of description logics through collaboration and innovation. </p>

<body>
    <div class="sponsors-grid">
        <div class="sponsor-logo" onclick="window.open('https://perspicuous-computing.science', '_blank')">
            <img src="/assets/images/cpec2.png" alt="DFG grant 389792660 as part of TRR 248-CPEC" class="tooltip">
        </div>
       <!-- <div class="sponsor-logo" onclick="window.open('https://google.com', '_blank')">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2f/Google_2015_logo.svg/2560px-Google_2015_logo.svg.png" alt="Google">
        </div>-->
    </div>
</body>
