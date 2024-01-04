# anime_recc
Currently 4 models have been implemented,

Content-based filtering(con_fil):
- Genre-based
- Synopsis-based
These models have implementations for calculating the similarity between two anime, e.g.
![image](https://github.com/jhlimm8/anime_recc/assets/103594440/5ea4c799-4dae-48ba-a001-a0a8d7d6a9ba)


Collaborative filtering(col_fil):
- Item-item similarity
- Matrix Factorization
Along with similarity implementations, these models have additional implementations for rating prediction, e.g.
![image](https://github.com/jhlimm8/anime_recc/assets/103594440/39fbf454-02ee-4222-98d1-ef99fcff7b58)

The learnt models for Matrix Factorization are saved as model_weights.pth(int) files, where (int) is the epoch the model was saved. 

To Do:
  Make a user-facing system that uses said models.
