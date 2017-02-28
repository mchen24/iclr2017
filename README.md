# Doc2VecC

code from the paper [Efficient Vector Representation for Documents Through Corruption](https://openreview.net/pdf?id=B1Igu2ogg).

## Acknowledge

The code was modified from Thomas Mikolov's code on Paragraph Vector.
https://groups.google.com/forum/#!msg/word2vec-toolkit/Q49FIrNOQRo/J6KG8mUj45sJ

## Dependencies

You will need to download the liblinear package, and change the path to the package in the script accordingly. 
https://www.csie.ntu.edu.tw/~cjlin/liblinear/

## Getting started

Run the script go.sh, it will download the IMDB movie review dataset, and learn document representations on this dataset. A linear SVM is trained on the learned representation fo sentiment analysis. 


## Reference

If you found this code useful, please cite the following paper:

Minmin Chen. **"Efficient Vector Representation for Documents Through Corruption."** *5th International Conference on Learning Representations, ICLR (2017).*

    @article{chen2017efficient,
      title={Efficient Vector Representation for Documents Through Corruption},
      author={Chen, Minmin},
      journal={5th International Conference on Learning Representations},
      year={2017}
    }

## License

[Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0)
