---
layout: page
permalink: /about/
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Resume</title>
    <style>
        body {
            font-family: 'Segoe UI', 'Helvetica Neue', Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f5f7fa;
            color: #333;
            line-height: 1.6;
            max-width: 900px;
            margin: 0 auto;
        }
        
        header {
            background: linear-gradient(135deg, #1a237e 0%, #283593 100%);
            color: white;
            padding: 30px;
            border-radius: 8px;
            margin-bottom: 30px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        
        h1 {
            margin: 0;
            font-size: 2.5rem;
            font-weight: 700;
            text-align: center;
        }
        
        .subtitle {
            margin-top: 10px;
            font-size: 1.2rem;
            opacity: 0.9;
            font-weight: 300;
            text-align: center;
        }
        
        .section {
            background-color: white;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.08);
            margin-bottom: 30px;
        }
        
        h2 {
            color: #1a237e;
            margin-top: 0;
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 2px solid #f0f0f0;
            font-size: 1.5rem;
        }
        
        .intro-text {
            line-height: 1.7;
            font-size: 1.05rem;
        }
        
        .timeline {
            margin: 0;
            padding: 0;
            list-style-type: none;
        }
        
        .timeline-item {
            margin-bottom: 25px;
            position: relative;
            padding-left: 25px;
        }
        
        .timeline-item:last-child {
            margin-bottom: 0;
        }
        
        .timeline-item:before {
            content: "";
            position: absolute;
            left: 0;
            top: 5px;
            width: 12px;
            height: 12px;
            border-radius: 50%;
            background-color: #283593;
        }
        
        .timeline-item:after {
            content: "";
            position: absolute;
            left: 5px;
            top: 17px;
            width: 2px;
            height: calc(100% + 10px);
            background-color: #e0e0e0;
        }
        
        .timeline-item:last-child:after {
            display: none;
        }
        
        .year {
            display: inline-block;
            background-color: #e8eaf6;
            color: #1a237e;
            padding: 4px 12px;
            border-radius: 4px;
            font-weight: 600;
            margin-bottom: 8px;
            font-size: 0.95rem;
        }
        
        .position {
            font-weight: 600;
            color: #283593;
            margin-bottom: 5px;
            font-size: 1.1rem;
        }
        
        .company {
            color: #555;
            margin-bottom: 5px;
        }
        
        footer {
            margin-top: 30px;
            text-align: center;
            color: #666;
            font-size: 0.9rem;
            padding-top: 20px;
            border-top: 1px solid #ddd;
        }
        
        @media (max-width: 768px) {
            body {
                padding: 15px;
            }
            
            h1 {
                font-size: 2rem;
            }
            
            header {
                padding: 20px;
            }
            
            .section {
                padding: 20px;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Zhuoyang Liu</h1>
    </header>
    
    <section class="section">
        <h2>Personal Introduction</h2>
        <div class="intro-text">
            <p>My name is Zhuoyang Liu(as the order in Chinese, Liu Zhuo Yang in Mandarin or Lieu Tsoh Yan in Goetian). I was born in Shanghai in 2005. I'm now an undergraduate student in the school of mathematical science in East China Normal University.</p>
            <p>I'm interested in algebraic number theory, especially for the theory of p-adic analysis and Langlands program.</p>
            <p>Except for maths, I like to play table tennis. Recently, I also swim and sing more than before.
        </div>
    </section>
    
    <section class="section">
        <h2>Education/Career Experience</h2>
        <ul class="timeline">
            <li class="timeline-item">
                <div class="year">2023 - Present</div>
                <div class="position">Undergraduate student</div>
                <div class="company">East China Normal University</div>
            </li>
            
            <li class="timeline-item">
                <div class="year">2020 - 2023</div>
                <div class="position">Senior middle school student</div>
                <div class="company">High School Affiliated to Shanghai Jiaotong University</div>
            </li>
            
            <li class="timeline-item">
                <div class="year">2016 - 2020</div>
                <div class="position">Junior middle school student</div>
                <div class="company">Shanghai Peijia Bilingual School</div>
            </li>
            
            <li class="timeline-item">
                <div class="year">2011 - 2016</div>
                <div class="position">Primary school student</div>
                <div class="company">Shanghai Peijia Bilingual School</div>
            </li>
        </ul>
    </section>
    
    <footer>
        <p>Copyright &copy by Zhuoyang Liu</p>
        <p>Contact: 10231510466@stu.ecnu.edu.cn</p>
    </footer>
</body>
</html>
