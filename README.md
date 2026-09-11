FluidX 是一个UE5.8开发的NiagaraGPU交互水系统,基于浅水方程算法，依赖网格体距离场实现水面障碍物检测和水波自动生成。
使用说明：
将BP_FluidX_Water放入场景即可，如需焦散，则需要把水下的场景打包为Actor，添加AC_CausticsDMICreator组件，并在场景大纲中选择组件，指定BP_FluidX的默认值为要关联焦散的水体BP_FluidX_WaterActor实例。
已支持大型开放水域的模拟窗口跟随玩家，由BP_FluidX_Water的FollowMode开关控制。
支持设置模拟边界的属性，Wall或者OpenWater，由BP_FluidX_Water的BoundaryMode控制。
<img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/c2a09564-471f-4ae2-b80f-4f5c0a3703db" />

<img width="2465" height="1304" alt="image" src="https://github.com/user-attachments/assets/94f8d4b6-237e-4525-ad46-366c00e412e2" />
