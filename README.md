We used Transfer Learning with the goal of achieving 75% accuracy on the Food 101 dataset.

We concluded with two EfficientNet models. For the first model, we began by feature extraction with all layers frozen and then gradually fine-tuned the model until it stopped learning repeatedly until all layers were unfrozen.
Contrary to what we initially thought, the accuracy obtained by fine-tuning was lower than otherwise.

Results:

>Model 1: Fine-tuning. Accuracy: 70.8%

>Model 2: Without fine-tuning. Accuracy: 81.2%

Project Features

We used TensorFlow’s:
DataSets (loaded from)

Data API (prepared and batched datasets)

* Prefetching
   
* Parallelizing
   
Callbacks

* Early Stopping
   
* Adaptive Learning Rate
   
* Checkpointing
   
Enabled Mixed Precision Training

* Leveraged Google Colab’s  free GPUs to drastically accelerate computation.
   
TensorBoard

   Created tensor board to visualize training histories of both models.
