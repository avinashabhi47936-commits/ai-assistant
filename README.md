<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Malla Reddy Campus AI App - Project Estimate</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #ff6b35, #f7931e);
            min-height: 100vh;
            padding: 20px;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            background: white;
            border-radius: 20px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            overflow: hidden;
        }
        
        .header {
            background: linear-gradient(135deg, #ff6b35, #f7931e);
            padding: 30px;
            text-align: center;
            color: white;
        }
        
        .header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            font-weight: 700;
        }
        
        .header p {
            font-size: 1.2rem;
            opacity: 0.9;
        }
        
        .content {
            padding: 40px;
        }
        
        .section {
            margin-bottom: 40px;
            padding: 25px;
            background: #fafafa;
            border-radius: 15px;
            border-left: 5px solid #ff6b35;
        }
        
        .section h2 {
            color: #ff6b35;
            margin-bottom: 20px;
            font-size: 1.5rem;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .icon {
            width: 24px;
            height: 24px;
            background: #ff6b35;
            border-radius: 50%;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 12px;
            font-weight: bold;
        }
        
        .phase {
            background: white;
            padding: 20px;
            margin: 15px 0;
            border-radius: 10px;
            border: 1px solid #e0e0e0;
            transition: all 0.3s ease;
        }
        
        .phase:hover {
            box-shadow: 0 5px 15px rgba(255, 107, 53, 0.1);
            border-color: #ff6b35;
        }
        
        .phase-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 15px;
        }
        
        .phase-title {
            font-weight: 600;
            color: #333;
            font-size: 1.1rem;
        }
        
        .phase-duration {
            background: #ff6b35;
            color: white;
            padding: 5px 12px;
            border-radius: 20px;
            font-size: 0.9rem;
            font-weight: 600;
        }
        
        .phase-details {
            color: #666;
            line-height: 1.6;
        }
        
        .cost-breakdown {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        
        .cost-item {
            background: white;
            padding: 20px;
            border-radius: 10px;
            text-align: center;
            border: 2px solid #f0f0f0;
        }
        
        .cost-amount {
            font-size: 2rem;
            font-weight: 700;
            color: #ff6b35;
            margin-bottom: 10px;
        }
        
        .cost-label {
            color: #666;
            font-weight: 500;
        }
        
        .total-summary {
            background: linear-gradient(135deg, #ff6b35, #f7931e);
            color: white;
            padding: 30px;
            border-radius: 15px;
            text-align: center;
            margin-top: 30px;
        }
        
        .total-amount {
            font-size: 3rem;
            font-weight: 700;
            margin-bottom: 10px;
        }
        
        .total-timeline {
            font-size: 1.3rem;
            opacity: 0.9;
        }
        
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
            margin-top: 20px;
        }
        
        .feature-card {
            background: white;
            padding: 15px;
            border-radius: 8px;
            border-left: 4px solid #ff6b35;
        }
        
        .assumptions {
            background: #fff3e0;
            border: 1px solid #ffcc80;
            border-radius: 10px;
            padding: 20px;
            margin-top: 20px;
        }
        
        .assumptions h3 {
            color: #e65100;
            margin-bottom: 15px;
        }
        
        .assumptions ul {
            color: #bf360c;
            padding-left: 20px;
        }
        
        .assumptions li {
            margin-bottom: 8px;
        }
        
        @media (max-width: 768px) {
            .header h1 {
                font-size: 2rem;
            }
            
            .content {
                padding: 20px;
            }
            
            .total-amount {
                font-size: 2.5rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>🎓 Malla Reddy Campus AI Assistant</h1>
            <p>Complete Project Estimate & Timeline</p>
        </div>
        
        <div class="content">
            <div class="section">
                <h2><span class="icon">🎯</span>Project Scope</h2>
                <div class="features-grid">
                    <div class="feature-card">
                        <strong>🏛️ Campus Facilities</strong>
                        <p>Room booking, maintenance, hours</p>
                    </div>
                    <div class="feature-card">
                        <strong>🍽️ Dining Services</strong>
                        <p>Menus, hours, nutrition info</p>
                    </div>
                    <div class="feature-card">
                        <strong>📚 Library Services</strong>
                        <p>Book search, study spaces, hours</p>
                    </div>
                    <div class="feature-card">
                        <strong>📋 Admin Procedures</strong>
                        <p>Forms, deadlines, contact info</p>
                    </div>
                    <div class="feature-card">
                        <strong>💬 Conversational AI</strong>
                        <p>Natural language processing</p>
                    </div>
                    <div class="feature-card">
                        <strong>🌐 Web Application</strong>
                        <p>Responsive, mobile-friendly</p>
                    </div>
                </div>
            </div>
            
            <div class="section">
                <h2><span class="icon">⏱️</span>Development Timeline</h2>
                
                <div class="phase">
                    <div class="phase-header">
                        <span class="phase-title">Phase 1: Planning & Design</span>
                        <span class="phase-duration">3-4 weeks</span>
                    </div>
                    <div class="phase-details">
                        Requirements gathering, UI/UX design with orange theme, database schema design, AI conversation flow mapping
                    </div>
                </div>
                
                <div class="phase">
                    <div class="phase-header">
                        <span class="phase-title">Phase 2: Backend Development</span>
                        <span class="phase-duration">6-8 weeks</span>
                    </div>
                    <div class="phase-details">
                        AI model setup, API development, database implementation, integration with campus systems, conversation engine
                    </div>
                </div>
                
                <div class="phase">
                    <div class="phase-header">
                        <span class="phase-title">Phase 3: Frontend Development</span>
                        <span class="phase-duration">4-6 weeks</span>
                    </div>
                    <div class="phase-details">
                        Web app development, chat interface, responsive design, orange theme implementation, mobile optimization
                    </div>
                </div>
                
                <div class="phase">
                    <div class="phase-header">
                        <span class="phase-title">Phase 4: Testing & Deployment</span>
                        <span class="phase-duration">2-3 weeks</span>
                    </div>
                    <div class="phase-details">
                        AI training with campus data, user testing, bug fixes, deployment setup, staff training, go-live
                    </div>
                </div>
            </div>
            
            <div class="section">
                <h2><span class="icon">💰</span>Cost Breakdown</h2>
                <div class="cost-breakdown">
                    <div class="cost-item">
                        <div class="cost-amount">₹8-12L</div>
                        <div class="cost-label">Development Team<br>(3-4 months)</div>
                    </div>
                    <div class="cost-item">
                        <div class="cost-amount">₹2-3L</div>
                        <div class="cost-label">AI Infrastructure<br>(Annual)</div>
                    </div>
                    <div class="cost-item">
                        <div class="cost-amount">₹1-2L</div>
                        <div class="cost-label">Design & Testing<br></div>
                    </div>
                    <div class="cost-item">
                        <div class="cost-amount">₹50K-1L</div>
                        <div class="cost-label">Deployment & Setup<br></div>
                    </div>
                </div>
            </div>
            
            <div class="total-summary">
                <div class="total-amount">₹12-18 Lakhs</div>
                <div class="total-timeline">15-21 weeks (4-5 months)</div>
                <p style="margin-top: 15px; opacity: 0.9;">Complete campus AI assistant with ongoing support</p>
            </div>
            
            <div class="section">
                <h2><span class="icon">⚡</span>Technology Stack</h2>
                <div class="features-grid">
                    <div class="feature-card">
                        <strong>Frontend</strong>
                        <p>React.js, TypeScript, Orange UI theme</p>
                    </div>
                    <div class="feature-card">
                        <strong>Backend</strong>
                        <p>Node.js/Python, REST APIs</p>
                    </div>
                    <div class="feature-card">
                        <strong>AI Engine</strong>
                        <p>OpenAI GPT/Local LLM, RAG system</p>
                    </div>
                    <div class="feature-card">
                        <strong>Database</strong>
                        <p>PostgreSQL/MongoDB</p>
                    </div>
                    <div class="feature-card">
                        <strong>Hosting</strong>
                        <p>AWS/Azure cloud infrastructure</p>
                    </div>
                    <div class="feature-card">
                        <strong>Integration</strong>
                        <p>Campus systems APIs</p>
                    </div>
                </div>
            </div>
            
            <div class="assumptions">
                <h3>⚠️ Key Assumptions & Variables</h3>
                <ul>
                    <li><strong>Team:</strong> 1 Project Manager, 2 Web Developers, 1 Backend Developer, 1 AI Engineer, 1 UI/UX Designer</li>
                    <li><strong>PWA Benefits:</strong> Works offline, installs like app, push notifications, fast loading</li>
                    <li><strong>Student Access:</strong> Any smartphone browser - no app store needed</li>
                    <li><strong>Hosting:</strong> ₹15-30K/month for cloud hosting (AWS/Azure)</li>
                    <li><strong>Updates:</strong> Instant updates - no waiting for app store approval</li>
                    <li><strong>Maintenance:</strong> ₹2-3L annually for hosting, updates, AI costs</li>
                    <li><strong>Launch:</strong> Can go live immediately, students access via college.edu/app</li>
                </ul>
            </div>
        </div>
    </div>
</body>
</html>
