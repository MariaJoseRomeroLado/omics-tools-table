# omics-tools-table
This repository contains a table that summarizes some of the available tools for analyzing omics data. 

  <table id="toolsTable" class="display">
    <thead>
      <tr>
        <th>Tool</th>
        <th>Category</th>
        <th>Description</th>
        <th>Link</th>
        <th>Comments</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>FastQC</td>
        <td>Analysis</td>
        <td>Quality control for sequencing data</td>
        <td><a href="https://www.bioinformatics.babraham.ac.uk/projects/fastqc/" target="_blank">Visit</a></td>
        <td>Great for identifying issues in raw reads</td>
      </tr>
      <tr>
        <td>Bowtie</td>
        <td>Sequencing</td>
        <td>Fast and memory-efficient aligner</td>
        <td><a href="http://bowtie-bio.sourceforge.net/index.shtml" target="_blank">Visit</a></td>
        <td>Often used in RNA-seq pipelines</td>
      </tr>
      <tr>
        <td>IGV</td>
        <td>Visualization</td>
        <td>Interactive genome viewer</td>
        <td><a href="https://software.broadinstitute.org/software/igv/" target="_blank">Visit</a></td>
        <td>Supports various genome formats</td>
      </tr>
      <tr>
        <td>Trimmomatic</td>
        <td>Analysis</td>
        <td>Trimming and filtering of reads</td>
        <td><a href="http://www.usadellab.org/cms/?page=trimmomatic" target="_blank">Visit</a></td>
        <td>Handles both single-end and paired-end data</td>
      </tr>
    </tbody>
  </table>

### 🆕 Adding New Tools
To add new tools to the existing table, replace the <tr> blocks inside <tbody> with rows for the new tools. Each row represents one tool.

_Example:_

```html
<tr>
  <td>Tool Name</td>
  <td>Category</td>
  <td>Short Description</td>
  <td><a href="URL" target="_blank">Visit</a></td>
  <td>Comments</td>
</tr>```


