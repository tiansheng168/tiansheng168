- 👋 Hi, I’m @tiansheng168
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
tiansheng168/tiansheng168 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
struct gameboar8192 has store,copy   {
       packed_space:u64,
       score : u64,
       last_tile:vector<u64>,
       top_tile: u64,
       game_over:bool
              
}
struct spaceposition has copy {
row: u8,
column: u8
}
