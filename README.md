<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Industry-Standard Tech Stack</title>
    <!-- Font Awesome & Devicon icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.15.1/devicon.min.css">
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
        }
 body {
            background-color: #0b0e14;
            color: #ffffff;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }
.container {
            width: 100%;
            max-width: 1000px;
            background-color: #0e1117;
            border: 1px solid #1f242d;
            border-radius: 12px;
            padding: 28px;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.6);
        }
 .header {
            text-align: center;
            margin-bottom: 24px;
            position: relative;
            padding-bottom: 16px;
            border-bottom: 1px solid #1f2937;
        }
.header h1 {
            font-size: 24px;
            font-weight: 700;
            letter-spacing: 0.5px;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            color: #f3f4f6;
        }
.header h1 span.bolt {
            color: #f59e0b;
        }
 .grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 16px;
        }
  @media (max-width: 768px) {
            .grid {
                grid-template-columns: 1fr;
            }
        }
.card {
            background-color: #12161f;
            border: 1px solid #1f2430;
            border-radius: 8px;
            padding: 20px;
            display: flex;
            flex-direction: column;
            gap: 16px;
        }
.card-title {
            font-size: 15px;
            font-weight: 600;
            color: #e5e7eb;
            display: flex;
            align-items: center;
            gap: 8px;
        }
 .pills-group {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }
 .pill-row {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
        }
 .pill {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            padding: 8px 14px;
            border-radius: 6px;
            font-size: 12px;
            font-weight: 700;
            letter-spacing: 0.5px;
            text-transform: uppercase;
            color: #ffffff;
            transition: transform 0.2s ease, filter 0.2s ease;
            cursor: default;
        }
  .pill:hover {
            transform: translateY(-2px);
            filter: brightness(1.1);
        }
 /* Colors */
        .pill-blue { background-color: #1d4ed8; }
        .pill-python { background-color: #2563eb; }
        .pill-pandas { background-color: #311b92; }
        .pill-numpy { background-color: #0284c7; }
        .pill-yellow { background-color: #d97706; }
        .pill-orange { background-color: #ea580c; }
        .pill-red { background-color: #dc2626; }
        .pill-cyan { background-color: #0891b2; }
        .pill-dark-blue { background-color: #1e3a8a; }
        .pill-purple { background-color: #7c3aed; }
        .pill-teal { background-color: #0d9488; }
        .pill-green { background-color: #16a34a; }
 /* Icons Row */
        .icons-row {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 4px;
        }
.icon-box {
            width: 38px;
            height: 38px;
            border-radius: 8px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 20px;
            color: #ffffff;
            transition: transform 0.2s ease;
        }
 .icon-box:hover {
            transform: scale(1.08);
        }
 .bg-cpp { background-color: #00599c; }
        .bg-python { background-color: #3776ab; }
        .bg-jupyter { background-color: #f37626; }
        .bg-docker { background-color: #2496ed; }
        .bg-git { background-color: #f05032; }
        .bg-github { background-color: #24292e; border: 1px solid #30363d; }
        .bg-linux { background-color: #2d3748; }
        .bg-vscode { background-color: #007acc; }
    </style>
</head>
<body>
 <div class="container">
        <div class="header">
            <h1><span class="bolt"><i class="fa-solid fa-bolt"></i></span> Industry-Standard Tech Stack</h1>
        </div>

  <div class="grid">
            <!-- Box 1: Data Analytics & Business Intelligence -->
            <div class="card">
                <div class="card-title">
                    <i class="fa-solid fa-chart-column" style="color: #60a5fa;"></i>
                    Data Analytics & Business Intelligence
                </div>
                <div class="pills-group">
                    <div class="pill-row">
                        <div class="pill pill-blue"><i class="devicon-postgresql-plain"></i> SQL</div>
                        <div class="pill pill-python"><i class="devicon-python-plain"></i> PYTHON</div>
                        <div class="pill pill-pandas"><i class="devicon-pandas-plain"></i> PANDAS</div>
                    </div>
                    <div class="pill-row">
                        <div class="pill pill-numpy"><i class="devicon-numpy-original"></i> NUMPY</div>
                        <div class="pill pill-yellow"><i class="fa-solid fa-chart-pie"></i> POWER BI</div>
                        <div class="pill pill-orange"><i class="fa-solid fa-table-cells"></i> TABLEAU</div>
                    </div>
                </div>
            </div>

            <!-- Box 2: Data Engineering & Cloud Data Stack -->
  <div class="card">
                <div class="card-title">
                    <i class="fa-solid fa-gear" style="color: #a78bfa;"></i>
                    Data Engineering & Cloud Data Stack
                </div>
                <div class="pills-group">
                    <div class="pill-row">
                        <div class="pill pill-blue"><i class="devicon-postgresql-plain"></i> POSTGRESQL</div>
                        <div class="pill pill-orange"><i class="fa-solid fa-cubes"></i> DBT</div>
                        <div class="pill pill-orange"><i class="fa-solid fa-fire"></i> APACHE SPARK</div>
                    </div>
                    <div class="pill-row">
                        <div class="pill pill-cyan"><i class="fa-solid fa-wind"></i> APACHE AIRFLOW</div>
                        <div class="pill pill-cyan"><i class="fa-solid fa-snowflake"></i> SNOWFLAKE</div>
                        <div class="pill pill-dark-blue"><i class="devicon-amazonwebservices-original"></i> AWS</div>
                    </div>
                </div>
            </div>

            <!-- Box 3: Software Engineering Fundamentals -->
   <div class="card">
                <div class="card-title">
                    <i class="fa-solid fa-brain" style="color: #f472b6;"></i>
                    Software Engineering Fundamentals
                </div>
                <div class="pills-group">
                    <div class="pill-row">
                        <div class="pill pill-blue"><i class="fa-solid fa-sitemap"></i> DATA STRUCTURES</div>
                        <div class="pill pill-orange"><i class="fa-solid fa-code"></i> ALGORITHMS</div>
                    </div>
                    <div class="pill-row">
                        <div class="pill pill-blue"><i class="fa-solid fa-cube"></i> OOP</div>
                        <div class="pill pill-purple"><i class="fa-solid fa-shapes"></i> SOLID PRINCIPLES</div>
                        <div class="pill pill-orange"><i class="fa-solid fa-diagram-project"></i> SYSTEM DESIGN</div>
                    </div>
                </div>
            </div>

            <!-- Box 4: Data Science & Environments (تعديل الـ AI إلى Data Science) -->
   <div class="card">
            <div class="card-title">
                    <i class="fa-solid fa-microscope" style="color: #38bdf8;"></i>
                    Data Science & Environments
                </div>
                <div class="pills-group">
                    <div class="pill-row">
                        <div class="pill pill-orange"><i class="devicon-scikitlearn-plain"></i> SCIKIT LEARN</div>
                        <div class="pill pill-blue"><i class="fa-solid fa-chart-line"></i> MATPLOTLIB</div>
                        <div class="pill pill-teal"><i class="fa-solid fa-wave-square"></i> SEABORN</div>
                    </div>
                    <div class="pill-row">
                        <div class="pill pill-purple"><i class="fa-solid fa-calculator"></i> SCIPY</div>
                        <div class="pill pill-green"><i class="fa-solid fa-square-poll-vertical"></i> STATSMODELS</div>
                    </div>
                </div>
                <div class="icons-row">
                    <div class="icon-box bg-cpp" title="C++"><i class="devicon-cplusplus-plain"></i></div>
                    <div class="icon-box bg-python" title="Python"><i class="devicon-python-plain"></i></div>
                    <div class="icon-box bg-jupyter" title="Jupyter Notebook"><i class="devicon-jupyter-plain"></i></div>
                    <div class="icon-box bg-docker" title="Docker"><i class="devicon-docker-plain"></i></div>
                    <div class="icon-box bg-git" title="Git"><i class="devicon-git-plain"></i></div>
                    <div class="icon-box bg-github" title="GitHub"><i class="devicon-github-original"></i></div>
                    <div class="icon-box bg-linux" title="Linux"><i class="devicon-linux-plain"></i></div>
                    <div class="icon-box bg-vscode" title="VS Code"><i class="devicon-vscode-plain"></i></div>
                </div>
            </div>
        </div>
    </div>

</body>
</html>
