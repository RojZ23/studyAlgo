<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>StudyAlgo · Final Exam Samples</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background: linear-gradient(145deg, #f6f9fc 0%, #e9f0f5 100%);
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
      padding: 1.5rem;
    }

    .card {
      max-width: 720px;
      width: 100%;
      background: rgba(255, 255, 255, 0.75);
      backdrop-filter: blur(6px);
      -webkit-backdrop-filter: blur(6px);
      border-radius: 2.5rem;
      padding: 2.8rem 2.2rem;
      box-shadow: 0 20px 40px -12px rgba(0, 20, 30, 0.25),
                  0 8px 24px -6px rgba(0, 0, 0, 0.05);
      border: 1px solid rgba(255, 255, 255, 0.5);
      transition: box-shadow 0.2s ease;
    }

    h1 {
      font-size: 2.1rem;
      font-weight: 600;
      letter-spacing: -0.02em;
      color: #0b2b3d;
      display: flex;
      align-items: center;
      gap: 0.5rem;
      margin-bottom: 0.3rem;
    }

    .subhead {
      font-size: 1rem;
      color: #2c4b5e;
      opacity: 0.8;
      font-weight: 400;
      border-left: 3px solid #2f7b9c;
      padding-left: 1rem;
      margin-bottom: 2.2rem;
      line-height: 1.4;
    }

    .button-grid {
      display: flex;
      flex-direction: column;
      gap: 1rem;
    }

    .exam-btn {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 1rem 1.6rem;
      background: white;
      border-radius: 1.8rem;
      border: 1px solid #dde7ed;
      text-decoration: none;
      color: #0b2b3d;
      font-weight: 500;
      font-size: 1.1rem;
      transition: all 0.2s ease;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.02);
      cursor: pointer;
    }

    .exam-btn:hover {
      background: #ffffff;
      border-color: #7bb3d1;
      box-shadow: 0 8px 18px -8px rgba(27, 86, 116, 0.2);
      transform: translateY(-2px);
    }

    .exam-btn:active {
      transform: scale(0.98);
      background: #f2f8fe;
    }

    .btn-label {
      display: flex;
      align-items: center;
      gap: 0.75rem;
      flex-wrap: wrap;
    }

    .badge {
      background: #e4eef5;
      border-radius: 40px;
      padding: 0.2rem 0.9rem;
      font-size: 0.75rem;
      font-weight: 600;
      letter-spacing: 0.02em;
      color: #1b5674;
      text-transform: uppercase;
    }

    .arrow {
      color: #6f92a8;
      font-size: 1.2rem;
      transition: transform 0.2s ease;
    }

    .exam-btn:hover .arrow {
      transform: translateX(4px);
      color: #1b6b8f;
    }

    .footer-note {
      margin-top: 2.2rem;
      font-size: 0.85rem;
      color: #3b5e72;
      border-top: 1px solid #d3e0e9;
      padding-top: 1.4rem;
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
      gap: 0.5rem;
    }

    .footer-note span {
      background: #e4eef5;
      padding: 0.2rem 0.9rem;
      border-radius: 30px;
      font-size: 0.75rem;
      font-weight: 500;
      color: #1d4b61;
    }

    /* subtle icon */
    .icon {
      display: inline-block;
      width: 1.2rem;
      text-align: center;
    }

    @media (max-width: 480px) {
      .card {
        padding: 1.8rem 1.2rem;
        border-radius: 1.8rem;
      }

      h1 {
        font-size: 1.6rem;
      }

      .exam-btn {
        padding: 0.8rem 1.2rem;
        font-size: 1rem;
      }
    }
  </style>
</head>
<body>
  <div class="card" role="main">
    <h1>
      <span class="icon">📘</span> StudyAlgo
    </h1>
    <div class="subhead">
      Final exam practice — worked solutions
    </div>

    <div class="button-grid">
      <!-- Final Exam Sample 1 -->
      <a 
        href="https://rojz23.github.io/studyAlgo/sample_final_solutions.html" 
        target="_blank" 
        rel="noopener noreferrer"
        class="exam-btn"
      >
        <span class="btn-label">
          <span style="font-size: 1.2rem;">📄</span>
          Final Exam Sample 1
          <span class="badge">summer 2020</span>
        </span>
        <span class="arrow">→</span>
      </a>

      <!-- Final Exam Sample 2 -->
      <a 
        href="https://rojz23.github.io/studyAlgo/index%20(4).html" 
        target="_blank" 
        rel="noopener noreferrer"
        class="exam-btn"
      >
        <span class="btn-label">
          <span style="font-size: 1.2rem;">📄</span>
          Final Exam Sample 2
          <span class="badge">fall 2017</span>
        </span>
        <span class="arrow">→</span>
      </a>
    </div>

    <div class="footer-note">
      <span>🔗 opens in new tab</span>
      <span>ch. 1–8 · ch. 1–13, 18, 22–23</span>
    </div>
  </div>
</body>
</html>
