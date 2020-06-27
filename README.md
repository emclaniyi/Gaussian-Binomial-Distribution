# Gaussian-Binomial-Distribution

# my_gnb_distributions
gnb_distributions is a python library for finding the gaussian and binomial distribution of a dataset.

## installation
use the package manager [pip] to install gnb_distribution


```bash
pip install my_gnb_distribution
```

## Usage

```python
from distributions import Gaussian
from distributions import Binomial

gaussian = Gaussian()
gaussian.read_data_file('numbers.txt')
gaussian.data
gaussian.mean
gaussian.stdev
gaussian.calculate_mean()
gaussian.calculate_stdev()
gaussian.pdf()

`same applies to Binomial distribution`
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
