MCIC-COCO is a machine comprehension dataset that is generated based on the
publicly available COCO dataset. The technique to create such a dataset
is reported in the paper:

"Understanding Image and Text Simultaneously: a Dual Vision-Language Machine
Comprehension Task",
Nan Ding, Sebastian Goodnman, Fei Sha, Radu Soricut

We generate a datasets of over half-million examples,
on which we estimate that the human-level accuracy is in the 83% range
(in a 5-way multi-choice setup; for comparison, a random-guess approach has 20%
accuracy).
A novel neural-network architecture that combines the representation power
of recursive neural networks with the discriminative power of fully-connected
multi-layered networks (see above cited paper) achieves the best result as of
the date of the dataset publication: 60.8% on the test set.

What is enclosed in this package is the MCIC-COCO dataset.

Datasets needed:
D1. COCO images (train_2014 and val_2014).
    [Image data available for download at:
     http://mscoco.org/dataset/#download].
D2. The MCIC-COCO dataset that comes with this package, see data/

How to read MCIC-COCO dataset:
Each line of the MCIC-COCO dataset is one example, which contains the following
fields:
answer_[0-4]: 5 candidate captions (tokenized) for the image. All captions come
              from captions_train2014.json and captions_val2014.json of the COCO
              dataset.
image:        the image filename from train_2014 or val_2014 of the COCO images
example_id:   a unique string id for each example
reference:    the answer index of the true caption (0 to 4)

Note: Due to Google open-source policy, we replaced three sensitive words from the original dataset to "j*llyfish", "f*cking", "s*upid". 