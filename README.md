# Messy_vs_clean_rooms
Machine learning model to classify images

$ python label_image.py \
    --graph=rooms.pb \
    --labels=rooms.txt \
    --input_layer=Placeholder \
    --output_layer=final_result \
    --image=/path/to/new_image.jpg
