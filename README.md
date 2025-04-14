1️⃣ requirement
document： requirements.txt
cleaning data from rearview

get unique images
combine unique images with annotations(4 datasets)
match image_id with the id in CVAT
rename category into six classes
split data into train and test(8:2) #i didnt do it here
2️⃣ restore object name
pedestrian-rider	car	truck-bus-train
human	vehicle	vehicle
motorcycle-bicycle	traffic light	traffic sign
bike	traffic light	traffic sign
3️⃣ embedding
purpose : to generate the 2D or 3D representation that is visualized output : hoping to categorize images that are alike



note: embeddings for 4342 images


note: embeddings for 3433 images
4️⃣ uniqueness
purpose : building a representation that relates the samples to each other, and analyze this representation to output uniqueness scores for each sample output : populates a uniqueness field on each sample that contains the sample’s uniqueness score



note: delete uniqueness lower then 0.08 by embeddings
5️⃣ brightness
purpose : to analyze images brightness out : mean of brightness

clarity purpose : to analyze images clartiy output : variable of Laplacian



conclusion:x-axis represent brightness, y-axis represent clarity. By the two dimension plot we can tell most pictures aren't clarity, and the brightness of pictures lend in the middle of the plot.

