> **zigzag3** is a **[Zigzag brush](zigzag-brush)** that generates zigzag patterns between three colors.

- [Parameters](#parameters)
- [Direction](#direction)
- [Examples](#examples)

## Parameters

- **Direction**: Direction of the pattern (see below)
- **Width A**: Width of the primary lines
- **Width B**: Width of the secondary lines
- **Width C**: Width of the tertiary lines
- **Color A**: Color of the primary line
- **Color B**: Color of the secondary line
- **Color C**: Color of the tertiary line

Setting any of the colors to `0` will result in missing voxels.

## Direction

<table>
    <tr>
        <td width="50%"><img src="https://s3.amazonaws.com/misc.lachlanmcdonald.com/magicavoxel-shaders/0.10.2/zigzag3_direction0.png" alt="Example of a direction of 0"></td>
        <td width="50%"><img src="https://s3.amazonaws.com/misc.lachlanmcdonald.com/magicavoxel-shaders/0.10.2/zigzag3_direction1.png" alt="Example of a direction of 1"></td>
    </tr>
    <tr>
        <td>Dirction: <code>0</code></td>
        <td>Dirction: <code>1</code></td>
    </tr>
    <tr>
        <td width="50%"><img src="https://s3.amazonaws.com/misc.lachlanmcdonald.com/magicavoxel-shaders/0.10.2/zigzag3_direction2.png" alt="Example of a direction of 2"></td>
        <td width="50%"><img src="https://s3.amazonaws.com/misc.lachlanmcdonald.com/magicavoxel-shaders/0.10.2/zigzag3_direction3.png" alt="Example of a direction of 3"></td>
    </tr>
    <tr>
        <td>Dirction: <code>2</code></td>
        <td>Dirction: <code>3</code></td>
    </tr>
</table>

## Examples

<table>
    <tr>
        <td width="33%"><img src="https://s3.amazonaws.com/misc.lachlanmcdonald.com/magicavoxel-shaders/0.10.2/zigzag3_example0.png" alt="Example"></td>
        <td width="33%"><img src="https://s3.amazonaws.com/misc.lachlanmcdonald.com/magicavoxel-shaders/0.10.2/zigzag3_example1.png" alt="Example"></td>
        <td width="33%"><img src="https://s3.amazonaws.com/misc.lachlanmcdonald.com/magicavoxel-shaders/0.10.2/zigzag3_example2.png" alt="Example"></td>
    </tr>
</table>