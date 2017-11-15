This project generates animations of pytorch optimizers solving toy problems. Examples Below.

[Some nice animations](http://www.denizyuret.com/2015/03/alec-radfords-animations-for.html) were posted a few years ago by Alex Radford but didn't include the Adam optimizer or landscapes with noise.  [Louis Tiao](http://louistiao.me/notes/visualizing-and-animating-optimization-algorithms-with-matplotlib/) blogged about how to make the visualizations. The [pytorch unit tests](https://github.com/pytorch/pytorch/blob/master/test/test_optim.py) show how to run the optimizers on test functions. I pulled these together and shared the result at https://github.com/wassname/viz_torch_optim. Please make some better animations and share them.

# Examples

![](docs/videos/beales.gif)

![](docs/videos/six_humped_camel_back_20171115_09-38-57.gif)
![](docs/videos/six_humped_camel_back_20171115_09-38-57_3d.gif)
![](docs/videos/six_humped_camel_back_20171115_09-38-57_loss.gif)

![](docs/videos/madsen_20171115_10-04-15_3d.gif)
![](docs/videos/madsen_20171115_10-04-15_loss.gif)

![](docs/videos/rosenbrock_20171115_09-47-52.gif)

![](docs/videos/beales_20171115_07-18-03_3d.gif) 


# Usage:

- `git clone https://github.com/wassname/viz_torch_optim`
- `jupyter notebook`
- open main.ipynb
- install any missing dependencies with pip
