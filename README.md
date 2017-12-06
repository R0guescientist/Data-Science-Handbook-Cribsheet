# Data Science Handbook Cribsheet
Intro to Numpy, Pandas, Matplotlib and Scikit-Learn. Condensed from Python Data Science Handbook (@jakevdp)

| File  | Notes  | To Do  |
|:-:|---|---|
|__Numpy__ | Placeholder | - |
|    |     |     |
|__Pandas__|-        |-    |-     |
|[Objects](Pandas-Objects.ipynb)                            | Series, DataFrames, Indexes | - |
|[Indexing & Selection](Pandas-Indexing-and-Selection.ipynb)| - | - |
|[Operations](Pandas-Operations.ipynb)                      | - | - |
|[Missing Values](Pandas-Missing-Values.ipynb)              | - | - |
|[Hierarchical Indexing](Pandas-Hierarchical-Indexing.ipynb)| MultiIndex, stack(), unstack(), reset_index() | - |
|[Concat & Append](Pandas-Concat-And-Append.ipynb)          | concat(), append() | - |
|[Merge & Join](Pandas-Merge-and-Join.ipynb)                | merge(), query()   |     |
|[Aggregation & Grouping](Pandas-Aggregation-and-Grouping.ipynb)| sum(), mean(), median(), describe(), groupby(), aggregate(), filter(), transform(), apply() |     |
|[Pivot Tables](Pandas-Pivot-Tables.ipynb)| pivot_table(), cut(), qcut()  |   |
|[Vectorized String Ops](Pandas-Vectorized-String-Ops.ipynb) | - | Hacked-up rev of Recipe DB example  |
|Time Series placeholder | datetime64(), Timestamp(), DateTimeIndex(), Period(), TimeDelta(), to_datetime(), date_range(), pandas-datareader | Wait for [Google Finance URL bug fix](https://github.com/pydata/pandas-datareader/issues/426) |
|[High Perf Ops](Pandas-Performance-Eval-and-Query.ipynb)| numexpr, eval(), query(), nbytes() | - |
|     |     |     |
|__Matploblib__ |-     |-     |
|[Intro](Matplotlib-Intro.ipynb)   | style.use(), savefig(), image(), canvas.get_supported_filetypes(),  | -  |
|[3D plotting](Matplotlib-3D-Plotting.ipynb) | mplot3d, axes(projection='3d'), plot3D(), scatter3D(), contour3D(), plot_wireframe(), plot_surface(),plot_trisurf() | -  |
|[Colorbars](Matplotlib-Custom-Colorbars.ipynb) | - | -  |
|[Legends](Matplotlib-Custom-Legends.ipynb)   | - | -  |
|[Ticks (Tickmarks)](Matplotlib-Custom-Tickmarks.ipynb)   | - | -  |
|[Density & Contour Plots](Matplotlib-Density-and-Contour-Plots.ipynb)   | - | -  |
|[Errorbars](Matplotlib-Errorbars.ipynb)   | - | Debug GaussianProcessRegressor in sklearn 0.19  |
|[Geo Data with Basemap](Matplotlib-Geo-Data-With-Basemap.ipynb)   | - | Update to Matplotlib 2.0  |
|[Histograms](Matplotlib-Histograms-and-Bins.ipynb)   | - | -  |
|[Line Plots](Matplotlib-Line-Plots.ipynb)   | - | -  |
|[Subplots](Matplotlib-Multiple-Subplots.ipynb)   | - | -  |
|[Scatter Plots](Matplotlib-Scatter-Plots.ipynb)   | - | -  |
|[Settings & Stylesheets](Matplotlib-Settings-and-Stylesheets.ipynb)   | - | -  |
|[Text & Annotation](Matplotlib-Text-and-Annotation.ipynb)   | - | -  |
|                          |     |     |
|__Scikit-Learn__ | - | - |
|[Intro to ML](05.01-What-Is-Machine-Learning.ipynb) | - | - |
|[Intro to Scikit-Learn](05.02-Introducing-Scikit-Learn.ipynb) | - | - |
|[Hyperparameters & Model Validation](05.03-Hyperparameters-and-Model-Validation.ipynb) | - | - |
|[Feature Engineering](05.04-Feature-Engineering.ipynb)| DictVectorizer, get_feature_names, fit_transform, OneHotEncoder, FeatureHasher, CountVectorizer, TdifVectorizer, PolynomialFeatures, Imputer, make_pipeline | - |
|[Naive Bayes](05.05-Naive-Bayes.ipynb) | GaussianNB, predict_proba, MultinomialNB | - |
|[Linear Regression](05.06-Linear-Regression.ipynb) | LinearRegression, PolynomialFeatures, Ridge, Lasso | - |
