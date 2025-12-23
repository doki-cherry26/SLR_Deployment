# SLR_Deployment
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Height vs Weight Prediction</title>
    <style>
        body {
            font-family: Arial, Helvetica, sans-serif;
            line-height: 1.6;
            margin: 40px;
            background-color: #f9f9f9;
            color: #333;
        }
        h1, h2, h3 {
            color: #2c3e50;
        }
        ul {
            margin-left: 20px;
        }
        code {
            background-color: #eee;
            padding: 2px 6px;
            border-radius: 4px;
            font-family: Consolas, monospace;
        }
        .container {
            background: #ffffff;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        footer {
            margin-top: 40px;
            font-size: 0.9em;
            color: #555;
        }
    </style>
</head>
<body>

<div class="container">

    <h1>📊 Height vs Weight Prediction using Linear Regression</h1>

    <h2>📌 Project Overview</h2>
    <p>
        This project demonstrates a simple Machine Learning regression model to
        predict a person’s <strong>weight based on their height</strong> using
        <strong>Linear Regression</strong>. It follows a complete ML workflow including
        data loading, preprocessing, model training, prediction, and evaluation.
    </p>

    <h2>🎯 Objective</h2>
    <p>
        To build a Linear Regression model that learns the relationship between
        <strong>Height</strong> (independent variable) and <strong>Weight</strong>
        (dependent variable) and predicts weight accurately.
    </p>

    <h2>📁 Dataset</h2>
    <ul>
        <li><strong>File name:</strong> <code>data.csv</code></li>
        <li><strong>Columns:</strong>
            <ul>
                <li>Height → Input feature</li>
                <li>Weight → Target variable</li>
            </ul>
        </li>
    </ul>

    <h2>🛠️ Technologies Used</h2>
    <ul>
        <li>Python</li>
        <li>NumPy</li>
        <li>Pandas</li>
        <li>Matplotlib</li>
        <li>Scikit-learn</li>
    </ul>

    <h2>🔄 Project Workflow</h2>

    <h3>1️⃣ Import Required Libraries</h3>
    <p>All necessary libraries for data processing, visualization, and machine learning are imported.</p>

    <h3>2️⃣ Load Dataset</h3>
    <p>The dataset is loaded using Pandas and stored in a DataFrame.</p>

    <h3>3️⃣ Feature Selection</h3>
    <ul>
        <li><strong>X (Independent Variable):</strong> Height</li>
        <li><strong>y (Dependent Variable):</strong> Weight</li>
    </ul>

    <h3>4️⃣ Train-Test Split</h3>
    <p>
        The dataset is split into:
    </p>
    <ul>
        <li>80% Training Data</li>
        <li>20% Testing Data</li>
    </ul>

    <h3>5️⃣ Create Training and Testing DataFrames</h3>
    <p>
        Separate DataFrames are created to clearly observe training and testing data.
    </p>

    <h3>6️⃣ Model Building</h3>
    <p>
        A Linear Regression model is created using Scikit-learn and trained on the
        training dataset.
    </p>

    <h3>7️⃣ Model Parameters</h3>
    <ul>
        <li><strong>Coefficient:</strong> Indicates how weight changes with height</li>
        <li><strong>Intercept:</strong> Predicted weight when height is zero</li>
    </ul>

    <h3>8️⃣ Prediction</h3>
    <p>
        The trained model predicts weight values using the training data.
    </p>

    <h3>9️⃣ Model Evaluation</h3>
    <p>
        The model is evaluated using the <strong>R² Score</strong>, which measures how
        well the model explains the variance in the target variable.
    </p>

    <h2>📈 Results</h2>
    <p>
        The model successfully learns the relationship between height and weight.
        A higher R² score indicates better prediction accuracy.
    </p>

    <h2>✅ Conclusion</h2>
    <p>
        This project provides a beginner-friendly example of Linear Regression,
        data preprocessing, model training, and evaluation using Scikit-learn.
    </p>

    <h2>🚀 Future Enhancements</h2>
    <ul>
        <li>Add data visualization (scatter plot and regression line)</li>
        <li>Test the model on unseen data</li>
        <li>Use multiple features for improved accuracy</li>
    </ul>

    <footer>
        <p>⭐ Feel free to fork, modify, and experiment with this project!</p>
    </footer>

</div>

</body>
</html>
