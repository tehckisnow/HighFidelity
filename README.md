# HighFidelity
Assets for High Fidelity

Y - followed directions on https://docs.highfidelity.com/create-and-explore/avatars/blender-workflow which includes scaling in blender by 0.01.
     Result: 100x too large. using HiFI's avatar scaling slider has a negligible effect.
Y2 - scaled down to 1/100th in blender export menu.
     Result: Model is invisible and can't walk or double-click teleport.
Y3 - exported from blender just like Y and scaled down to 1/100th in HIF's "Package model as FST" menu.
     Result: Same result as Y2.
After reviewing Y3, I noticed that the model Y is not actually very large, but the camera moves as if it is very large, and other avatars are pushed away as if it is large.  Upon zooming in as much as I am able, it appears that the avatar is normal-sized.
