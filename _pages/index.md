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
<p>The 39th International Workshop on Description Logics will be held in Lisbon, Portugal, from July 17 to July 19, 2026. It will be co-located with several events as part of <a href="https://www.floc26.org/">FLoC 2026</a>, including <a href="https://kr.org/KR2026/">KR 2026</a> and <a href="https://nmr.krportal.org/2026/">NMR 2026</a>.</p>


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
        
        .speaker-title {
            margin-top: -20px;
            font-size: 0.9rem;
            color: gray;
            font-style: italic;
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
            padding: 20px;
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
            max-height: 90px;
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
                <p class="speaker-affiliation"><i class="fas fa-university"></i>University of Cape Town</p>
                <div class="speaker-title">Joint Talk with NMR, sponsored by CPEC</div>
                <div class="speaker-talk">
                    <p class="talk-title">Defeasible Reasoning</p>
                    <p style="font-size:smaller;">Preferential approaches to defeasible reasoning have turned out to be particularly promising for the propositional case, mainly because they are based on an elegant, comprehensive, and well-studied framework for non-monotonic reasoning proposed by Kraus, Lehmann, and Magidor—often referred to as the KLM approach. In the first part of this talk I will provide an introduction to propositional KLM-style defeasible reasoning. This will be followed by an overview of attempts to extend KLM-style defeasible reasoning beyond propositional logic. More specifically, I’ll look at the application of the KLM approach to description logics and some restricted first-order logics. In doing so, I’ll describe what has worked well, but also what are the (many) remaining challenges.</p>
                </div> 
            </div>
        </div>
        
        <!-- Speaker 2 -->
        <div class="speaker-card" onclick="window.open('https://lat.inf.tu-dresden.de/~stefborg/', '_blank')">
            <img src="/assets/images/SB.jpg" alt="Stefan Borgwardt" class="speaker-img">
            <div class="speaker-info">
                <h3 class="speaker-name">Stefan Borgwardt</h3>
                <p class="speaker-affiliation"><i class="fas fa-university"></i>TU Dresden, Germany</p>
                <div class="speaker-title">Sponsored by CPEC</div>
                <div class="speaker-talk">
                    <p class="talk-title">Explaining Description Logic Reasoning</p>
                    <p style="font-size:smaller;">While logic-based reasoning is explainable in theory, understanding the explanations often requires expert training and a lot of time. For explaining consequences entailed by description logic ontologies, the main form of explanations are justifications that pinpoint the axioms responsible for an entailment. However, with large justifications or expressive logics, it can be hard to see why the entailment follows from the justification. In recent years, we have studied approaches for computing proofs, which consist of simple steps for explaining an entailment, but may contain many such steps. We investigated different methods of computing proofs that are optimized according to some quality criteria, such as the size or depth of the proof. In addition to evaluating these ideas on existing description logic ontologies, we have conducted a series of user studies to find out how to best present proofs to users of description logic ontologies. Moreover, we implemented our algorithms in the Protégé plug-in Evee, which can not only explain why an entailment holds, but also why an expected entailment does not follow from the ontology.</p>
                </div>
            </div>
        </div> 
        
        <!-- Speaker 3 -->
       <div class="speaker-card" onclick="window.open('https://logic-in.cs.tu-dortmund.de/personen/profs/jean-christoph-jung/', '_blank')">
            <img src="/assets/images/jean2.png" alt="Jean Christoph Jung" class="speaker-img">
            <div class="speaker-info">
                <h3 class="speaker-name">Jean Christoph Jung</h3>
                <p class="speaker-affiliation"><i class="fas fa-university"></i>TU Dortmund, Germany</p>
                <div class="speaker-title">Sponsored by ScaDS.AI</div>
                <div class="speaker-talk">
                    <p class="talk-title">Computing Interpolants in Description Logics</p>
                    <p style="font-size:smaller;">Interpolants have a wide range of applications in description logics. For example, they serve as explanations for given complicated entailments, they can be used as explicit definitions for concepts in ontology construction, and they can be regarded as fitting concepts in description logic concept learning. In all these applications, the actual interpolants are needed and hence we need methods to compute them. While the computation problem has been thoroughly studied for description logics enjoying the Craig Interpolation Property, the corresponding theory for logics lacking that property is still underdeveloped. In this talk, I will report on first steps towards a better understanding of the computation of interpolants in such cases.</p>
                </div>
            </div>
        </div> 
    </section>
</body>

<!-- Sponsors Section -->
## Our Sponsors
<p>We extend our sincere gratitude to our sponsors for their generous support. Their contributions help advance the field of description logics through collaboration and innovation. </p>

<body>
    <div class="sponsors-grid">    
        <div class="sponsor-logo" onclick="window.open('https://scads.ai/', '_blank')">
            <img src="/assets/images/ScaDS-Logo2023_rgb.jpg" alt="ScaDS.AI-Center for Scalable Data Analytics and Artificial Intelligence Dresden/Leipzig" class="tooltip">
        </div>
        
        <div class="sponsor-logo" onclick="window.open('https://perspicuous-computing.science', '_blank')">
            <img src="/assets/images/cpec2.png" alt="DFG grant 389792660 as part of TRR 248-CPEC" class="tooltip">
        </div>
        
        <div style="background-color: #f2986c;" class="sponsor-logo" onclick="window.open('https://aij.ijcai.org', '_blank')">
            <img style="max-height:90pt" src="/assets/images/ARTINT_Logo2_c_highresolution.png" alt="AIJ" class="tooltip">
        </div>
        
        <!--<div style="background-color: rgb(40, 61, 121);" class="sponsor-logo" onclick="window.open('https://www.floc26.org/', '_blank')">
            <img style="max-height:100pt" src="/assets/images/floc_blue.png" alt="FLoC 2026" class="tooltip">
        </div>-->
    </div>
</body>
